# Libft

Libft is my own and first C library. This library contains a lot of general purpose functions that will be of good use for bigger projects. 

## Project description

Libft is the first project in the curriculum of school 42. It is a project that introduces you to programming, creating a good structure for your project and implementing basic function structures. The project consists of 3 parts. 
1. Re-writing a set of functions from the libc such as strlen, strchr, atoi etc.
2. Write a set of functions that are either not in the libc, or that are part of it but in a different form.
3. Write 9 bonus functions including structs 

### Norm writing

This project is written in accordance to the norm of school 42. Some of the most important norm rules are:
- Each function has a maximum of 25 lines
- One single variable declaration per line, all variables on top of the function 
- After the variable declarations, a newline will split them with the rest of the function
- No for loops allowed


## Install and run the project

First, clone my repository on your computer via the green "code" button on top of this page.
All the functions can be compiled using my Makefile. This Makefile has several options:
- run <code>make</code> to create object files for all the standard functions, and a archive library libft.a
- run <code>make bonus</code> to compile all the bonus functions.
- run <code>make clean</code> to delete all the object files
- run <code>make fclean</code> to delete all the object files and the libft.a file.
- run <code>make re</code> recompile the library.
