# ft_printf. School_42 project
This is my own implementation of the libc’s printf function.

## Usage
Run **make** to compile library (libftprintf.a). You can include ftprintf/ft.h and compile your program with library.

Use it like usual printf function. It supports:
1. specifiers: CSDOUcsdouixX%pfFn;
2. length flags: hh, h, l, ll, j, z, t, L;
3. flags: +-0[space]`#;
4. width and precision data, including '*'.

This isn't perfect. Have some problems with big floats.
