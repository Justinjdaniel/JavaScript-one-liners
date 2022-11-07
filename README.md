# JavaScript One Liners

## Table of content

- Copy text to clipboard
- Check if the current user is on an Apple device

## Copy text to clipboard

```javascript
const copyToClipboard = text =>
    (navigator.clipboard?.writeText?.(text));
```

## Check if the current user is on an Apple device

```javascript
const isAppleDevice =/Mac|iPod|iPhone|iPad/.text(navigator.platform);

console.log(isAppleDevice)
// Result: will return true if user is on an Apple device.
```
