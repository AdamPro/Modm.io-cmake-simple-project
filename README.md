# Modm.io-cmake-simple-project
Simple project for STM Discovery F3 board using modm.io library and CMake.

# Prerequisites:
* GCC (min. 7) for arm
* CMake
* lbuild (instruction can be found [here](https://modm.io/guide/installation/)) 

# Build
1. Clone this repository
2. Download submodules: `git submodule update --init --recursive`
3. Build HAL using: `lbuild build`
3. Create build directory: `mkdir cmake-gcc-arm`
4. Go inside new directory `cd cmake-gcc-arm`
5. Genate build system using `cmake ..`
6. Build: `make`
7. You're ready to flash your device :)
