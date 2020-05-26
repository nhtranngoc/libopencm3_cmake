# README

This is the smallest-possible example program using libopencm3.

It's intended for the ST STM32F429IDISCOVERY eval board. It should blink
the GREEN LED on the board.

## Board connections

*none required*

# CMake Integration

This is a modified version of `libopencm3`'s `miniblink` project, using CMake instead of the usual Makefile system. This will also generate a .bin in addition to .elf 

## Compile

To compile, run:

```shell
cd build
cmake ..
make
```