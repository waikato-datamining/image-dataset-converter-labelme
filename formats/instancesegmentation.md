# Instance segmentation

For instance segmentation (i.e., polygons), [labelme](https://github.com/wkentaro/labelme) 
uses JSON files, storing the objects as list under the `shapes` property.
Each shape has a `label` and a `points` property. The latter is a list of
`[x, y]` pairs. The `shape_type` is `polygon`.


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
          250.8142292490119,
          107.33596837944665
        ],
        ...
        [
          270.81422924901193,
          121.33596837944665
        ]
      ],
      "group_id": null,
      "shape_type": "polygon",
      "flags": {}
    },
    {
      "label": "person",
      "points": [
        [
          482.81422924901193,
          87.18098682963114
        ],
        ...
        [
          499.81422924901193,
          92.18098682963114
        ]
      ],
      "group_id": 0,
      "shape_type": "polygon",
      "flags": {}
    },
    {
      "label": "person",
      "points": [
        [
          370.81422924901193,
          170.33596837944665
        ],
        [
          366.81422924901193,
          173.33596837944665
        ],
        [
          365.81422924901193,
          182.33596837944665
        ],
        [
          368.81422924901193,
          185.33596837944665
        ]
      ],
      "group_id": 0,
      "shape_type": "polygon",
      "flags": {}
    },
    {
      "label": "bottle",
      "points": [
        [
          374.81422924901193,
          159.33596837944665
        ],
        ...
        [
          382.81422924901193,
          159.33596837944665
        ]
      ],
      "group_id": null,
      "shape_type": "polygon",
      "flags": {}
    },
    {
      "label": "__ignore__",
      "points": [
        [
          338.81422924901193,
          266.3359683794467
        ],
        ...
        [
          370.81422924901193,
          270.3359683794467
        ]
      ],
      "group_id": null,
      "shape_type": "polygon",
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

https://github.com/wkentaro/labelme/tree/main/examples/instance_segmentation

