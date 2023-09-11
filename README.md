# square-imagehttps://github.com/hunj/square-image/tree/main
adds a blurry background to fit a portrait-size image into a square. appends `_edit` at the end of the file name.

# requirements
- Python 3.11
- Pillow

# usage
Single file
```bash
$ python resizer.py <path-to-image-file>
```

Also supports directory
```bash
python resizer.py /path/to/directory
```

# example

## sample input

![sample input](https://raw.githubusercontent.com/hunj/square-image/main/sample/HJL_9546.jpg)

## sample output
![sample result](https://raw.githubusercontent.com/hunj/square-image/main/sample/HJL_9546_edit.jpg)
