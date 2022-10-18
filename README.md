printf is a is a custom implementation of the C programming function printf. Group project done by Robert Maina Njoroge and Jeane Okello. ALX Cohrot 9 2022.

Prototype: int _printf(const char *, ...);

Examples

String

    Input: _printf("%s\n", 'This is a string.');
    Output: This is a string.

Character

    Input: _printf("The first letter in the alphabet is %c\n", 'A');
    Output: The first letter in the alphabet is A

Integer

    Input: _printf("There are %i dozens in a gross\n", 12);
    Output: There are 12 dozens in a gross

Decimal:

    Input: _printf("%d\n", 1000);
    Output: 1000

Requirements.
-Allowed editors: vi, vim, emacs
-All your files will be compiled on Ubuntu 20.04 LTS using gcc, using the options -Wall -Werror -Wextra -pedantic -std=gnu89
-All your files should end with a new line
-A README.md file, at the root of the folder of the project is mandatory
-Your code should use the Betty style. It will be checked using betty-style.pl and betty-doc.pl
-You are not allowed to use global variables
-No more than 5 functions per file
-The prototypes of all your functions should be included in your header file called main.h

Authorized functions and macros
-write (man 2 write)
-malloc (man 3 malloc)
-free (man 3 free)
-va_start (man 3 va_start)
-va_end (man 3 va_end)
-va_copy (man 3 va_copy)
-va_arg (man 3 va_arg)

Compilation.
-Your code will be compiled using gcc -Wall -Werror -Wextra -pedantic -std=gnu89 *.c

FIle descriptions.

