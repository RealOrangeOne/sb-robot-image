# robot-image

Packer scripts to build SourceBots robot image

## Requirements

- Docker
- This repository, cloned with submodules (`git submodule update --init` / `git clone --recursive`)

## Usage

Simply run the `./build-image.sh` script. Packer will download all needed files and save the output image to `output.img`, ready for further compression and/or distribution.
