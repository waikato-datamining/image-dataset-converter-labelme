# from-labelme-od

* generates: idc.api.ObjectDetectionData

Loads the bounding box and/or polygon definitions from the associated labelme .json file.

```
usage: from-labelme-od [-h] [-l {DEBUG,INFO,WARNING,ERROR,CRITICAL}]
                       [-N LOGGER_NAME] [-i [INPUT ...]] [-I [INPUT_LIST ...]]

Loads the bounding box and/or polygon definitions from the associated labelme
.json file.

options:
  -h, --help            show this help message and exit
  -l {DEBUG,INFO,WARNING,ERROR,CRITICAL}, --logging_level {DEBUG,INFO,WARNING,ERROR,CRITICAL}
                        The logging level to use. (default: WARN)
  -N LOGGER_NAME, --logger_name LOGGER_NAME
                        The custom name to use for the logger, uses the plugin
                        name by default (default: None)
  -i [INPUT ...], --input [INPUT ...]
                        Path to the json file(s) to read; glob syntax is
                        supported (default: None)
  -I [INPUT_LIST ...], --input_list [INPUT_LIST ...]
                        Path to the text file(s) listing the json files to use
                        (default: None)
```
