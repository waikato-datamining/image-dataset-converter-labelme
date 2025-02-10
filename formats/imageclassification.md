# Image classification

For image classification, [labelme](https://github.com/wkentaro/labelme) uses
json files with the labels stored in under the `flags` key. The active
label has a value of `true` and all other ones `false`.

## Example

```json
{
  "version": "4.0.0",
  "flags": {
    "__ignore__": false,
    "cat": true,
    "dog": false
  },
  "shapes": [],
  "imagePath": "0001.jpg",
  "imageData": null,
  "imageHeight": 480,
  "imageWidth": 640
}
```

## Source

https://github.com/wkentaro/labelme/tree/main/examples/classification

