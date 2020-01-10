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

**C Is a Middle-Level Language 

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

