# GNUBoy SDL2 Port For Termux

SDL2-GNUBoy-Termux are the [SDL2-GNUboy](https://github.com/AlexOberhofer/SDL2-GNUBoy) compilation files adapted for easy complication in Termux.

A Multiplatform Gameboy Emulator. Free Software.

# Overview

GNUBoy is a cool, old piece of software. This fork focuses on a multiplatform SDL 2 port. Hopefully this codebase can be helpful to someone in the future or someone interested in learning about C, SDL, or emulator development.

Fork or contribute! Based on GNUBoy and licensed under GNU GPLv2

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


