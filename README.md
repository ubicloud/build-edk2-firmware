# build-edk2-firmware

This repository builds
[cloud-hypervisor](https://github.com/cloud-hypervisor/cloud-hypervisor/)
targeted firmware for both arm64 and x64.

If you want to run a build outside of a Github Action environment, try
the following in a Debian or Ubuntu environment:

```bash
# If you need build dependencies:
$ sudo apt-get update && sudo apt-get -y install uuid-dev iasl build-essential python3-distutils git libbrotli-dev nasm

$ ./build-edk2
```
