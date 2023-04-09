# Basics

C is a procedural programming language.  
It was initially developed by Dennis Ritchie as a system programming language to write an operating system. The main features of C language include low-level access to memory, simple set of keywords, and a clean style, these features make C language suitable for system programming like operating system or compiler development.  

## Basic Data Types in C
1. int: Stores whole numbers, without decimals  
2. float: Stores fractional numbers, containing one or more decimals. Sufficient for storing 6-7 decimal digits  
3. double: Stores fractional numbers, containing one or more decimals. Sufficient for storing 15 decimal digits  
4. char: 	Stores a single character/letter/number, or ASCII values. 

## Basic Format Specifiers  
1. int: %d or %i
2. float: %f
3. double: %lf
4. char: %c
5. string: %s

## main() function  
All valid C programs must contain the main() function.  
The code execution begins from the start of the main() function.  

## printf function 
The printf() is a library function to send formatted output to the screen.  
The function prints the string inside quotations.  
To use printf() in our program, we need to include **stdio.h** header file using the **#include <stdio.h>** statement.  

## scanf function
In C programming, scanf() is one of the commonly used function to take input from the user. The scanf() function reads formatted input from the standard input such as keyboards.  

## return 0
The return 0; statement inside the main() function is the "Exit status" of the program. It's optional.
