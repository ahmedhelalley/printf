# _printf :page_facing_up:

A formatted output conversion C program project, it was done as part of the Software Engineering track at ALX. This program is a similar version of the C standard library function, `printf`.

## Dependencies 

The `_printf` function was coded on an Ubuntu 20.04 LTS machine with `gcc` version 13.2.0.

## Usage 

To use the `_printf` function, the above dependencies should be installed, then
compile all `.c` files in the repository and include the header 'main.h' with
any main function.

Example `main.c`:
```
#include "main.h"

int main(void)
{
    _printf("Hello, World!");

    return (0);
}
```

Compilation:
```
$ gcc *.c -o tester
```

Output:
```
$ ./tester
Hello, World!
$
```

## Description :speech_balloon:

The function `_printf` prints output to stdout. The function prints
under the control of a `format` string that specifies how arguments are
converted for output.

Prototype: `int _printf(const char *format, ...);`

### Return Value

Upon successful return, `_printf` returns the number of characters printed
(excluding the terminating null byte used to end output to strings). 
If an output error is encountered, the function returns -1.

