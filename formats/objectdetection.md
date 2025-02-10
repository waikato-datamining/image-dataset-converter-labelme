# Object detection

For object detection (i.e., bounding boxes), [labelme](https://github.com/wkentaro/labelme) 
uses JSON files, storing the objects as list under the `shapes` property.
Each shape has a `label` and a `points` property. The latter is a list of
`[xmin, ymin]` and `[xmax, ymax]`. The `shape_type` is `rectangle`.


## Example

```json
{
  "version": "4.0.0",
  "flags": {},
  "shapes": [
    {
      "label": "person",
      "points": [
        [
          191.0,
          107.36900369003689
        ],
        [
          313.0,
          329.36900369003695
        ]
      ],
      "group_id": null,
      "shape_type": "rectangle",
      "flags": {}
    },
    {
      "label": "person",
      "points": [
        [
          365.0,
          83.0
        ],
        [
          500.0,
          333.0
        ]
      ],
      "group_id": null,
      "shape_type": "rectangle",
      "flags": {}
    }
  ],
  "imagePath": "2011_000003.jpg",
  "imageData": null,
  "imageHeight": 338,
  "imageWidth": 500
}
```


## Source

https://github.com/wkentaro/labelme/tree/main/examples/bbox_detection

