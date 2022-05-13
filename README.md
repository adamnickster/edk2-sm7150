## edk2-sm7150  
Forked from https://github.com/edk2-porting/edk2-sm7150  
  
## Building

Tested on:

Ubuntu 20.04 (x86_64 PC VM)

Ubuntu 22.04 (x86_64 PC VM)

Ubuntu 20.04 (aarch64 arm64 android chroot)

1. Setup

```bash
git clone https://github.com/edk2-porting/edk2-sm7150.git --depth=1
sudo apt install build-essential uuid-dev iasl git nasm python3-distutils gcc-aarch64-linux-gnu abootimg python-is-python3
cd edk2-sm7150
```

2. Build this project (only on linux)

```bash
bash build.sh
```

- Other devices:

```bash
bash DEVICEbuild.sh
```
(DEVICE is the codename of your phone.)

## Available Function  
  
 * USB (need extra power supply)  
 * UFS  
  
## Waiting for your tests.  
  
