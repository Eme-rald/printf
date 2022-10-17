printf

0x11.c - First project collaboration

OVERVIEW
Printf project is an ALX collaboration project. The task is to reproduce a program that operates in like manner as the printf function in the standard C stdio.h library.

Project source: Julien Barbier (CEO Holberton School). Language: C Programming

What you should learn from this project:
How to use git in a team setting applying variadic functions to a big project. The complexities of printf managing a lot of files and finding a good workflow.

REQUIREMENTS
General requirement are as follows:

Allowed editors: vi, vim, emacs

All your files will be compiled on Ubuntu 20.04 LTS using gcc, using the options -Wall -Werror -Wextra -pedantic -std=gnu89

All your files should end with a new line

A README.md file, at the root of the folder of the project is mandatory

Your code should use the Betty style. It will be checked using betty-style.pl and betty-doc.pl (https://github.com/holbertonschool/Betty/blob/master/betty-style.pl) 

You are not allowed to use global variables

No more than 5 functions per file

In the following examples, the main.c files are shown as examples. You can use them to test your functions, but you don’t have to push them to your repo (if you do we won’t take them into account). We will use our own main.c files at compilation. Our main.c files might be different from the one shown in the examples

The prototypes of all your functions should be included in your header file called main.h

Don’t forget to push your header file

All your header files should be include guarded

Note that we will not provide the _putchar function for this project

GitHub

There should be one project repository per group. The other members do not fork or clone the project to ensure only one of the team has the repository in their github account otherwise you risk scoring 0%

Authorized functions and macros

write (man 2 write)

malloc (man 3 malloc)

free (man 3 free)

va_start (man 3 va_start)

va_end (man 3 va_end)

va_copy (man 3 va_copy)

va_arg (man 3 va_arg)

TASKS
These are all the tasks of this project, the completed ones link to the corresponding files

0. I'm not going anywhere. You can print that wherever you want to. I'm here and I'm a Spur for life.
Write a function that produces output according to format.
c: converts input into character
s: converts input into string

1. Education is when you read the fine print. Experience is what you get if you don't.
Handle the following conversion specifiers:
d: converts input into base 10 integer
i: converts input into an integer
