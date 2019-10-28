# emushared
ongoing generic utilities support library for my emulator.

## build
~~~
git clone https://github.com/valerino/emushared
cd emushared
mkdir build && cd build
cmake ..
make

# setup environment variables to be used in external projects
export EMUSHARED_INCLUDE_PATH=/path/to/emushared
export EMUSHARED_LIB_PATH=/path/to/emushared/build
~~~

## sample usage
[my proof of concept c64 emulator](https://github.com/valerino/vc64-emu)
