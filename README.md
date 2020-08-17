## ico2gltf
Convert PlayStation 2 save icon models to glTF.

## Usage
```
$ ./ico2gltf.py -h
usage: ico2gltf.py [-h] [-o OUTPUT] [-m METADATA] [-q] input

Convert PS2 save icons to glTF.

positional arguments:
input                 Input file (.ico).

optional arguments:
-h, --help            show this help message and exit
-o OUTPUT, --output OUTPUT
Output file (.glb or .gltf). If not specified create a .glb file next to input file with the same file name.
-m METADATA, --metadata METADATA
Path to an icon.sys file with extra information to be embedded as an "extras" field.
-q, --quiet           Do not print any icon info.
```

## Support
 - Textures
 - Animations
 - Embedding icon.sys metadata