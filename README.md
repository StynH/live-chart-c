# live-chart-c
This is a pure-C fork of [lcallarec/live-chart](https://github.com/lcallarec/live-chart).
I made this because I wanted to use the library in a C project.

The `.vala` sources are compiled to `.c` using `valac --ccode` and built into a static library. No Vala compiler is required to use it.

## What’s included

Each release contains:

- `c-emitted/*.c` -> generated C source files  
- `c-emitted/*.h` -> generated headers  
- `c-emitted/liblivechart.a` -> compiled static library  

## Original project

Original repo: https://github.com/lcallarec/live-chart  
License: MIT.