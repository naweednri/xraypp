
# Xraypp

This repo is for managing the X-ray core and using it in a multi-node way.


![GitHub License](https://img.shields.io/github/license/naweednri/xraypp)   ![C++](https://img.shields.io/badge/C++-%2300599C.svg?logo=c%2B%2B&logoColor=white)   ![CMake](https://img.shields.io/badge/CMake-064F8C?logo=cmake&logoColor=fff)

## Features

- High performance/speed for managing the X-ray core
- Managing in a multi-node way
- Using minimum RAM


## Installation

Use the cmake for building it:
```bash
git clone https://github.com/naweednri/xraypp
```
### Server:
```bash
cd server && mkdir build && cd build
cmake ..
cmake --build .
```
### Node:
```bash
cd node && mkdir build && cd build
cmake ..
cmake --build .
```
## Contributing

Contributions are always welcome!
