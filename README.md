# libft
![](https://img.shields.io/badge/125%2F100-brightgreen)
## Description

libft is a project at 42 that involves creating a custom C library compiling a variety of standard and extra functions that can be reused in future projects. This library aims to mimic a subset of the C Standard Library functions, along with additional utility functions.

## Base Features

- Recreation of standard C library functions like `strlen`, `strcpy`, `strcmp`, etc.
- Creation of a set of utility functions to manipulate strings, numbers, and memory.

## Bonus Functionality

The bonus part of libft includes aditional functions that deal with basic operations in regards to linked lists, such as their creation and deletion.

## Compatibility & Size

![](https://img.shields.io/badge/WSL-0a97f5?style=for-the-badge&logo=linux&logoColor=white)
![](	https://img.shields.io/badge/mac%20os-000000?style=for-the-badge&logo=apple&logoColor=white)

![](https://img.shields.io/github/languages/code-size/moop250/libft?color=<COLOR>)

## Usage 

To clone the repository use:
```bash
git clone https://github.com/moop250/libft.git
```

Compilation & cleanup:

- `make` : Compiles the library and creates the archive.
- `make bonus` : Compiles the library + bonus funcitons and creates the archive.
- `make clean` : Cleans up all object files (.o).
- `make fclean` : Cleans up the object files and the libft.a library archive.
- `make re` : Does a make fclean followed by a make to recompile the library.

Example usage in a C program:
```C
#include "libft.h"

int main(void)
{
    char *s = "Hello, World!";
    size_t len = ft_strlen(s);
    // use other libft functions as needed
}
```
