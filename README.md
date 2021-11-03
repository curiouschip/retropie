# retropie

A script to flashing a RetroPie image and making it Pip compatible.

## Usage

  1. clone this repository
  2. download the base RetroPie image, making sure not to change the filename (the script expects a filename of the format `retropie-$release-$x.$y.$z-*.img.gz`)
  3. run `sudo ./mkretro $target_device $retropie_image_file`

RetroPie will be flashed to the target SD card, modified to be Pip compatible, then cloned/compressed into the current directory.

## Updating kernel

To bundle a new kernel replace the kernel package in the `packages` directory with the new file.
