# zoho

This repository contains the Yocto build configuration for the Raspberry Pi
4 64-bit target. The `poky` and `meta-raspberrypi` layers are tracked as Git
submodules on the `scarthgap` branch; generated build output is excluded.

Initialize the source layers and enter the build environment with:

```sh
git clone --recurse-submodules https://github.com/PiyushaMasurkar/ZOHO.git
cd ZOHO
source sources/poky/oe-init-build-env build
```
