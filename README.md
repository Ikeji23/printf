Custom printf function built as a project for the alx software engineering program similar to the original printf function with function prototype int _printf(const char *format, ...); 
Collaborators: Chinyere Priscilla Ikeji and Eleazer Mobuchi Uguw.

Authorized functions and macros: write, malloc, free, va_start, va_end, va_copy, va_arg

The Code will be compiled using: $ gcc -Wall -Werror -Wextra -pedantic -std=gnu89 -Wno-format *.c

Tasks
Write a function that produces output according to a format.
Prototype: int _printf(const char *format, ...);
Returns: the number of characters printed (excluding the null byte used to end output to strings)

Write output to stdout, the standard output stream

Handle the conversion specifiers c, s, %

Handle the following conversion specifiers: d, i

Handle the following custom conversion specifiers:

b: the unsigned int argument is converted to binary

Handle the following conversion specifiers: u, o, x, X

Use a local buffer of 1024 chars in order to call write as little as possible.

Handle the following custom conversion specifier:

S : prints the string.
Non printable characters (0 < ASCII value < 32 or >= 127) are printed this way: \x,
followed by the ASCII code value in hexadecimal (upper case - always 2 characters)

Handle the following conversion specifier: p

Handle the following flag characters for non-custom conversion specifiers: +, space, #

Handle the following length modifiers for non-custom conversion specifiers: l, h

Conversion specifiers to handle: d, i, u, o, x, X 

Handle the field width for non-custom conversion specifiers.

Handle the precision for non-custom conversion specifiers.

Handle the 0 flag character for non-custom conversion specifiers.

Handle the - flag character for non-custom conversion specifiers.

Handle the following custom conversion specifier: r (prints the reversed string)

Handle the following custom conversion specifier: R (prints the rot13'ed string)

(All the above options work well together.)
