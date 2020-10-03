## python3-arm-wheels

This repository contains a series of pre-built wheels for different arm architectures.
These were built on a docker container emulating the architectures via qemu.

Right now, the repo contains images for Python3.8 on arm/v7 and aarch64 architectures of the following packages:
- numpy 1.20.0
- pandas 1.2.0
- scikit-learn 0.24.0
- scipy 1.6.0

I mainly use these wheels as a way to quickly build docker images for my python projects that have to target arm architectures.

## License

All the wheels hosted in this repository are distributed under their orignial respective licenses, a copy of which can be found in each wheel directory.