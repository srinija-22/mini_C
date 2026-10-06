I developed a custom C preprocessor tool named mypreprocessor that processes C source files and generates an extended .i file.

Features:
Removes single-line `//` and multi-line `/* */` comments
Processes `#include` statements
Supports simple `#define` macros
Supports macros with arguments
Generates the processed output as a `.i` file
Uses modular programming with multiple `.c` and `.h` files
Includes a Makefile for compilation

Compilation
make
Execution
./mypreprocessor inputfile.c

The processed file will be generated as:
inputfile.i

Concepts Used : C Programming, File Handling, Command-Line Arguments, Macros, String Processing, Modular Programming, and Makefile.
