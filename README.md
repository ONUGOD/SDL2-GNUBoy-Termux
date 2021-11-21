# GNUBoy SDL2 Port For Termux

SDL2-GNUBoy-Termux is just a repository where the [SDL2-GNUBoy](https://github.com/AlexOberhofer/SDL2-GNUBoy) Makefiles are modified for installation in Termux.

# Overview

GNUBoy is a cool, old piece of software. This fork focuses on a multiplatform SDL 2 port. Hopefully this codebase can be helpful to someone in the future or someone interested in learning about C, SDL, or emulator development.

# Building

Install packages needed to compile and dependencies:

```
$ pkg up x11-repo clang make git -y && pkg i sdl2 -y
```
Clone github repository:

```
$ git clone https://github.com/ONUGOD/SDL2-GNUBoy-Termux
```
Enter project directory:

```
$ cd SDL2-GNUBoy-Termux
```
Build:

```
$ make
```
Install:

```
$ make install
```
Run:

```
$ sdl2gnuboy ./rom
```
Uninstall:

```
$ chmod +x remove && ./remove
```


