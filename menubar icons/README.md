This directory contains the images for the menubar/traybar. The content consists of:
  * SVG files for the colored version of each frame
  * png/ico files which are created from the svg files. These should not be edited or replaced
  manually.

## Build script
The png/ico files are generated using the script `/scripts/build-menubar-icons.sh` which can be
run from the root directory using
```sh
./scripts/build-menubar-icons.sh
```

The script creates all menubar images for all platforms.

### Dependencies
Imagemagick is required for the script to run.
