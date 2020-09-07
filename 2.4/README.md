## 2 Getting started

### Static Linking

We have two files.

* messageprinter.c
* main.c

The Main file calls the function: `print_message()`.

And the linker finds body of this function within the Message Printer file.

Giving an example of linking a program together that is spread over multiple files.


Note:

It is possible to get the c compiler to do all of this in one step:

$ cc -o main main.c messageprinter.c

