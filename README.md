# sdl_libraries

This repository is used to setup the develop environment of sdl for rk3288 board system.

## 1. Install the compiler.

### a) System requirement
Your operating system should be Ubuntu16.04 x64, other OS may be not compatible.

### b) Install gcc-arm-linux-gnueabihf and g++-arm-linux-gnueabihf by apt
```shell
$sudo apt install gcc-arm-linux-gnueabihf g++-arm-linux-gnueabihf
```
### c) Install support packages for 32-bit architecture
```shell
$sudo apt-get install lib32ncurses5 lib32z1 lib32stdc++6
```
## 2. Install all the libraries
Use script install.sh to install and uninstall.sh to uninstall, all files installed are recorded in install_record.txt.

Install:
```shell
$sudo ./install.sh
```

Uninstall:
```shell
$sudo ./uninstall.sh
```
