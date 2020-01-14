**<a name="Whatisit"></a>What is it?**

This is my self-study plan to learn C programing language and understand every aspect of it. 

**Table of content**

[What is it?](#Whatisit)

[Why use it?](#Whyuseit)

[How to use it?](#Howtouse)

[Part 1: Foundational C](#Part1)

[Part 2: The C99 Standard](#Part2)

[Part 3: The C99 Standard Library](#Part3)

[Part 4: Algorithms and Applications](#Part4)

[Part 5: Software Development Using C](#Part5)

[Part 6: A C Interpreter](#Part6)

**<a name="Whyuseit"></a>Why use it?**

There are hundreds to thousands of book you can find out there at the book store or ebook website. But **C: The Complete Reference, 4th edition by McGraw-Hill** is a must-read book that can help the beginners to get used to C programing language in the "easiest" way.

**<a name="Howtouse"></a>How to use it?**

This page's outline follow the original outline of **C: The Complete Reference, 4th edition by McGraw-Hill**. So it will be more comfortable for readers to follow.

**<a name="Part1"></a>Part 1: Foundational C**

**Chapter 1: An Overview of C**

**A Brief History of C**

In this section, we all noticed that C89/C99 is mentioned. So, what is the difference between them? 

*Comments* – In C99 we can use a line comment that begins with //

*Identifiers* – C89 requires compilers to remember the first 31 characters vs. 63 characters in C99
Only the first 6 characters of names with external linkage are significant in C89 (no case sensitive)
In C99, it is the first 31 characters and case of letters matters

*Keywords* – 5 new keywords in C99: inline, restrict, _Bool, _Complex, and _Imaginary

*Expressions*

In C89, the results of **/** and **%** operators for a negative operand can be rounded either up or down. The sign of **i % j** for negative i or j depends on the implementation.
In C99, the result is always truncated toward zero and the sign of **i % j** is the sign of i.

*Bool type* – C99 provides _Bool type and macros in stdbool.h

*Loops* – C99 allows to declare control variable(s) in the first statement of the **for** loop

*Arrays* – C99 has **designated initializers** and also allows to use **variable-length arrays**

*Functions* – one of the directly visible changes is:
In C89, declarations must precede statements within a block. In C99, it cam be mixed.

*Preprocessor* – e.g.,
-C99 allows macros with a variable number of arguments
-C99 introduces __func__ macro which behaves as a strin

*Input/Output* – conversion specification for the *printf() and *scanf() functions has been significantly changed in C99.

*<stdbool.h>* – macros false and true that denote the logical values 0 and 1, respectively

*<stdint.h>* – integer types with specified widths <inttypes.h> – macros for input/output of types specified in
<stdint.h>

*<complex.h>* – functions to perform mathematical operations on
complex numbers

*<tgmath.h>* – type-generic macros for easier call of functions
defined in <math.h> and <complex.h>

*<fenv.h>* – provides access to floating-point status flags and
control modes

**C Is a Middle-Level Language**

Middle-Level Language? The middle-level language lies in between the low-level and high-level language.

The middle-level programming language interacts with the abstraction layer of a computer system. It serves as the bridge between the raw hardware and programming layer of the computer system. The middle-level language is also known as the intermediate programming language and pseudo-language.

The middle-level language is an output of any programming language, which is known as source code. The source code is written in a high-level language. This kind of middle-level language is designed to improve the translated code before the processor executes it.

The C language is the middle-level language because it has only 32 keywords: it takes less translation time like low-level language. We can do many works of low-level language through C language. There is a different type of data types used in the C language. The four common data types which are: char, int, float, double, etc. Each data type plays a unique role in the C language.

In conclusion, the C Programing language is the middle-level language due to these strengths: 
-Fast and Efficient 
-Rich library functions
-Portable, Modularity
-Easy to extend 
-Variety of data type and dominant operators
-Recusion
-Structured 
-Simple
-Extensible
-Mid-level
-Pointers
(All the points mentioned above will be described further later in this book.)

**C Is a Structured Language**

What is **Structured Language** and **Non-Strutured Language**?

The **structured** programming language allows a programmer to code a program by dividing the whole program into smaller units or modules. Structured programming is not suitable for the development of large programs and does not allow reusability of any set of codes. It is a programming paradigm aimed at improving the quality, clarity, and access time of a computer program by the use of subroutines, block structures, for and while loops.

A program in a **non-structured** language usually consists of sequentially ordered commands, or statements, usually one in each line. The lines are usually numbered or may have labels: this allows the flow of execution to jump to any line in the program.

**C Is a Programmer's Language**

**Compilers vs. Interpreters**

You guys feel confused and cannot distinguish **compilers** vs. **interpreters**?

This post may give you more detail and help you to understand it better. [Difference Between Compiler and Interpreter](https://techdifferences.com/difference-between-compiler-and-interpreter.html)

In my opinion, myself can point out the difference between them in this way: After translated by the **compiler**, a file as .exe (just for example) will be generated. Next time you want to use that code again, just run that .exe file without re-translate. With **interpreter**, it translate every single line of the program and run it in the order. In the next time of use, it requires to re-traslate and run.

**The Form of a C Program**

In this section, the most important point we have to mind is uppercase and lowercase characters. They are totally different. For example, **else** and **ELSE** are two different word. **else** is a keyword while **ELSE** is not. 
Moreover, we must be careful before decide to use any word as a variable or function name. Make sure that it won't match the keyword in C program.
A program may consist of one or more functions. However, **main()** is the function will be called first when program execution begins. 

**The Library and Linking**



Chapter 2: Expressions

Chapter 3: Statements

Chapter 4: Array and Strings

Chapter 5: Pointers

Chapter 6: Functions

Chapter 7: Structures, Uninons, Enumerations, and typedef

Chapter 8: Console I/O

Chapter 9: File I/O

Chapter 10: The Preprocessor and Comments



**<a name="Part2"></a>Part 2: The C99 Standard**

Chapter 11: C99


**<a name="Part3"></a>Part 3: The C99 Standard Library**

Chapter 12: Linking, Libraries, and Headers

Chapter 13: I/O Functions

Chapter 14: String and Character Functions

Chapter 15: Mathematical Functions

Chapter 16: Time, Date, Localization Functions

Chapter 17: Dynmic Allocation Functions

Chapter 18: Utility Functions

Chapter 19: Wide-Character Functions

Chapter 20: Library Features Added by C99



**<a name="Part4"></a>Part 4: Algorithms and Applications**

Chapter 21: Sorting and Searching

Chapter 22: Queues, Stacks, Linked Lists, and Trees

Chapter 23: Sparse Arrays

Chapter 24: Expression Parsing and Evaluation

Chapter 25: 
AI-Based Problem Solving

**<a name="Part5"></a>Part 5: Software Development Using C**

Chapter 26: Building a Windows 2000 Skeleton

Chapter 27: Software Engineering Using C

Chapter 28: Efficiency, Porting, and Debugging



**<a name="Part6"></a>Part 6: A C Interpreter**

Chapter 29: A C Interpreter

