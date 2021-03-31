<h1 align="center"> Logic Programming in C </h1>

# Content

1. [Project Status](#projectstatus)
2. [About the Project](#abouttheproject)
3. [Project Description](#projectdescription)
4. [Chapter 1: The C Language](#chapter1)
    - [Chapter 1 - Part 1: Why C?](#chapter1part1)
    - [Chapter 1 - Part 1: History](#chapter1part2)
    - [Chapter 1 - Part 2: GCC MinGW Compiler Installation](#chapter1part2)
    - [Chapter 1 - Part 3: Code Blocks IDE Installation](#chapter1part3)
    - [Chapter 1 - Part 4: First Program in C](#chapter1part4)
5. [Chapter 2: Sequential Structures](#chapter2)
    - [Chapter 2 - Part 1: Arithmetic Expressions](#chapter2part1)
    - [Chapter 2 - Part 2: Variables](#chapter2part2)
    - [Chapter 2 - Part 3: Data Input](#chapter2part3)
    - [Chapter 2 - Part 4: Data Processing](#chapter2part4)
    - [Chapter 2 - Part 5: Data Output](#chapter2part5)
    - [Chapter 2 - Part 6: Mathematical Functions](#chapter2part6)
6. [Chapter 3: Conditional Structures](#chapter3)
    - [Chapter 3 - Part 1: Comparable Expressions](#chapter3part1)
    - [Chapter 3 - Part 2: Logical Expressions](#chapter3part2)
    - [Chapter 3 - Part 3: Simple Conditional Structure](#chapter3part3)
    - [Chapter 3 - Part 4: Compound Conditional Structure](#chapter3part4)
    - [Chapter 3 - Part 5: Chaining Conditional Structures](#chapter3part5)
7. [Chapter 4: Repetitive Structures](#chapter4)
    - [Chapter 4 - Part 1: While Repetitive Structure](#chapter4part1)
    - [Chapter 4 - Part 2: For Repetitive Structure](#chapter4part2)
8. [Chapter 5: Vectors](#chapter5)
    - [Chapter 5 - Part 1: Theory](#chapter5part1)
    - [Chapter 5 - Part 2: Declaration and Creation](#chapter5part2)
    - [Chapter 5 - Part 3: Access](#chapter5part3)
9. [Chapter 6: Matrices](#chapter6)
    - [Chapter 6 - Part 1: Theory](#chapter6part1)
    - [Chapter 6 - Part 2: Declaration and Creation](#chapter6part2)
    - [Chapter 6 - Part 3: Access](#chapter6part3)
10. [Usage](#usage)
11. [Contributors](#contributors)
12. [Contributing](#contributing)
13. [Roadmap](#roadmap)
14. [To Do](#todo)
15. [Contacts](#contacts)
16. [License](#license)

# Project Status <a name="projectstatus"></a>

Project Status: Under Development :warning:

# About the Project <a name="abouttheproject"></a>

This project have a propose to introduce the reader the basics of logic programming with C.

In my [GitHub profile][github-url], you will see repositories named as "logic-programming-in-(language name)-basics". This repositories concist in tutorials to introduce the reader the basics in logical programming using the most usable languages in the market.

The Introduction to Programming logic can be found in this [repository][introduction-url], where basic concepts about programming logic are covered.

[![Project][project-shield]][project-url] <!-- Put the link of the github page of the tutorial her -->

This tutorial was based in the course from Phd Professor [Nelio Alves - Algorithms and Programming Logical][logicalcourse-url], the Youtube Channel [DevSuperior][devsuperior-url] and the WikiBook [Programar em C][wikibbok-url]

# Project Description <a name="projectdescription"></a>

Logical Programming is the first step in the computer science course and the first skill to learn when you want to become a software developer.

Logical Programming have to be independet of what programming language you will use, because the logic always will be the same. 

The basic content of a programming logic course consists:

- Introduction: Algorithms, Programming Language, IDE, Compiler and Interpreter.
- Sequential Structures: Arithmetic Expressions, Variables, Data Input, Data Processing, Data Output and Mathematical Functions.
- Conditional Structures: Comparable Expressions, Logical Expressions, Simple Conditional Structure, Compound Conditional Structure and Chaining Conditional Structures.
- Repetitive Structures: While Repetitive Structure and For Repetitive Structure.
- Vectors: Theory, Declaration and Creation and Access.
- Matrices: Theory, Declaration, Creation and Access.
  
## <a name="chapter1"></a>Chapter 1: The C Language

#### <a name="chapter1part1"></a>Chapter 1 - Part 1: Why C?

Why C and not Java or Basic, or Perl? 

Languages like Java or Perl are languages based on bytecode interpreted by a virtual machine, therefore, it is not a code interpreted directly by the processor. 

Unlike many programming languages, C allows the programmer to address memory in much the same way as it would be done in Assembly. Languages like Java or Perl provide mechanisms that allow the programmer to do his job without having to worry about memory allocation or pointers. 

This is generally a good thing, since it is quite a lot of work to deal with memory allocation when writing applications with high-level algorithms. However, when dealing with low-level tasks such as those that a kernel has to perform, such as copying a set of bytes to a network card, direct access to memory is highly necessary - something that you can't do with Java. C can be directly compiled into machine code, so it is fast and efficient. In addition, C allows you to customize how to implement everything to the basics, such as memory allocation, allowing adaptations to improve performance. It is worth remembering that script or bytecode interpreting software, such as Java and Python, are written in languages such as C and C ++.

C is one of the most popular programming languages ​​for writing operating systems, such as Microsoft Windows, Mac OS X and GNU / Linux. Operating systems communicate directly with the hardware; there is no lower layer to mediate your requests. Originally, operating systems were written in Assembly language, which resulted in very fast and efficient code. However, writing an operating system in Assembly is a tedious (slow) process, and produces code that will work only on a CPU architecture, such as x86 or ARM. Writing an operating system in a high-level language, such as C, allows programmers to retrofit the operating system to various architectures without having to rewrite all the code. The Linux kernel is an example of an operating system written in C, with only a few sections of code written in Assembly, to be able to execute instructions that exist only in one or the other architecture and for some optimizations.

#### <a name="chapter1part2"></a>Chapter 1 - Part 2: GCC MinGW Compiler Installation

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer accumsan id neque ut tempor. Nulla facilisi. Aliquam eu eros fermentum, commodo est sed, pharetra est. 
Curabitur lacinia blandit turpis rhoncus varius. Proin vulputate orci nulla, nec porttitor nibh consequat in. Suspendisse ac neque ut massa commodo auctor in sed libero. 
Sed tincidunt mauris eu tempor malesuada. Mauris feugiat vitae risus quis iaculis.

#### <a name="chapter1part3"></a>Chapter 1 - Part 3: Code Blocks IDE Installation

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer accumsan id neque ut tempor. Nulla facilisi. Aliquam eu eros fermentum, commodo est sed, pharetra est. 
Curabitur lacinia blandit turpis rhoncus varius. Proin vulputate orci nulla, nec porttitor nibh consequat in. Suspendisse ac neque ut massa commodo auctor in sed libero. 
Sed tincidunt mauris eu tempor malesuada. Mauris feugiat vitae risus quis iaculis.

#### <a name="chapter1part4"></a>Chapter 1 - Part 4: First Program in C

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer accumsan id neque ut tempor. Nulla facilisi. Aliquam eu eros fermentum, commodo est sed, pharetra est. 
Curabitur lacinia blandit turpis rhoncus varius. Proin vulputate orci nulla, nec porttitor nibh consequat in. Suspendisse ac neque ut massa commodo auctor in sed libero. 
Sed tincidunt mauris eu tempor malesuada. Mauris feugiat vitae risus quis iaculis.

## <a name="chapter2"></a>Chapter 2: Sequential Structures

#### <a name="chapter2part1"></a>Chapter 2 - Part 1: Arithmetic Expressions

The following table shows all the arithmetic operators supported by the C language. Assume variable A holds 10 and variable B holds 20, then

   | Operator | Description                                                  | Example     |
   |:---------|:-------------------------------------------------------------|:------------|
   | +        | Adds two operands.                                           | A + B = 30  |
   | −        | Subtracts second operand from the first.                     | A − B = -10 |
   | *        | Multiplies both operands.                                    | A * B = 200 |
   | /        | Divides numerator by de-numerator.                           | B / A = 2   |
   | %        | Modulus Operator and remainder of after an integer division. | B % A = 0   |
   | ++       | Increment operator increases the integer value by one.       | A++ = 11    |
   | --       | Decrement operator decreases the integer value by one.       | A-- = 9     |
   
```c
#include <stdio.h>

main() {

   int a = 21;
   int b = 10;
   int c ;

   c = a + b;
   printf("Line 1 - Value of c is %d\n", c );
   
   // Output: Line 1 - Value of c is 31
	
   c = a - b;
   printf("Line 2 - Value of c is %d\n", c );
   
   // Output: Line 2 - Value of c is 11
	
   c = a * b;
   printf("Line 3 - Value of c is %d\n", c );
   
   // Output: Line 3 - Value of c is 210
	
   c = a / b;
   printf("Line 4 - Value of c is %d\n", c );
   
   // Output: Line 4 - Value of c is 2
	
   c = a % b;
   printf("Line 5 - Value of c is %d\n", c );
   
   // Output: Line 5 - Value of c is 1
	
   c = a++; 
   printf("Line 6 - Value of c is %d\n", c );
   
   // Output: Line 6 - Value of c is 21
	
   c = a--; 
   printf("Line 7 - Value of c is %d\n", c );
   
   // Output: Line 7 - Value of c is 22
   
   return 0;
}
```

#### <a name="chapter2part2"></a>Chapter 2 - Part 2: Variables

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer accumsan id neque ut tempor. Nulla facilisi. Aliquam eu eros fermentum, commodo est sed, pharetra est. 
Curabitur lacinia blandit turpis rhoncus varius. Proin vulputate orci nulla, nec porttitor nibh consequat in. Suspendisse ac neque ut massa commodo auctor in sed libero. 
Sed tincidunt mauris eu tempor malesuada. Mauris feugiat vitae risus quis iaculis.

<div align="center"><img src="img/img-example-w5688-h3713.jpg" width=300 height=300><br><sub>Fig 1 - Aplication Deploy</sub></div>

#### <a name="chapter2part3"></a>Chapter 2 - Part 3: Data Input

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer accumsan id neque ut tempor. Nulla facilisi. Aliquam eu eros fermentum, commodo est sed, pharetra est. 
Curabitur lacinia blandit turpis rhoncus varius. Proin vulputate orci nulla, nec porttitor nibh consequat in. Suspendisse ac neque ut massa commodo auctor in sed libero. 
Sed tincidunt mauris eu tempor malesuada. Mauris feugiat vitae risus quis iaculis.

<div align="center"><img src="img/img-example-w5688-h3713.jpg" width=300 height=300><br><sub>Fig 1 - Aplication Deploy</sub></div>

#### <a name="chapter2part4"></a>Chapter 2 - Part 4: Data Processing

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer accumsan id neque ut tempor. Nulla facilisi. Aliquam eu eros fermentum, commodo est sed, pharetra est. 
Curabitur lacinia blandit turpis rhoncus varius. Proin vulputate orci nulla, nec porttitor nibh consequat in. Suspendisse ac neque ut massa commodo auctor in sed libero. 
Sed tincidunt mauris eu tempor malesuada. Mauris feugiat vitae risus quis iaculis.

<div align="center"><img src="img/img-example-w5688-h3713.jpg" width=300 height=300><br><sub>Fig 1 - Aplication Deploy</sub></div>

#### <a name="chapter2part5"></a>Chapter 2 - Part 5: Data Output

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer accumsan id neque ut tempor. Nulla facilisi. Aliquam eu eros fermentum, commodo est sed, pharetra est. 
Curabitur lacinia blandit turpis rhoncus varius. Proin vulputate orci nulla, nec porttitor nibh consequat in. Suspendisse ac neque ut massa commodo auctor in sed libero. 
Sed tincidunt mauris eu tempor malesuada. Mauris feugiat vitae risus quis iaculis.

<div align="center"><img src="img/img-example-w5688-h3713.jpg" width=300 height=300><br><sub>Fig 1 - Aplication Deploy</sub></div>

#### <a name="chapter2part6"></a>Chapter 2 - Part 6: Mathematical Functions

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer accumsan id neque ut tempor. Nulla facilisi. Aliquam eu eros fermentum, commodo est sed, pharetra est. 
Curabitur lacinia blandit turpis rhoncus varius. Proin vulputate orci nulla, nec porttitor nibh consequat in. Suspendisse ac neque ut massa commodo auctor in sed libero. 
Sed tincidunt mauris eu tempor malesuada. Mauris feugiat vitae risus quis iaculis.

<div align="center"><img src="img/img-example-w5688-h3713.jpg" width=300 height=300><br><sub>Fig 1 - Aplication Deploy</sub></div>

## <a name="chapter3"></a>Chapter 3: Conditional Structures

#### <a name="chapter3part1"></a>Chapter 3 - Part 1: Comparable Expressions

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer accumsan id neque ut tempor. Nulla facilisi. Aliquam eu eros fermentum, commodo est sed, pharetra est. 
Curabitur lacinia blandit turpis rhoncus varius. Proin vulputate orci nulla, nec porttitor nibh consequat in. Suspendisse ac neque ut massa commodo auctor in sed libero. 
Sed tincidunt mauris eu tempor malesuada. Mauris feugiat vitae risus quis iaculis.

<div align="center"><img src="img/img-example-w5688-h3713.jpg" width=300 height=300><br><sub>Fig 1 - Aplication Deploy</sub></div>

#### <a name="chapter3part2"></a>Chapter 3 - Part 2: Logical Expressions

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer accumsan id neque ut tempor. Nulla facilisi. Aliquam eu eros fermentum, commodo est sed, pharetra est. 
Curabitur lacinia blandit turpis rhoncus varius. Proin vulputate orci nulla, nec porttitor nibh consequat in. Suspendisse ac neque ut massa commodo auctor in sed libero. 
Sed tincidunt mauris eu tempor malesuada. Mauris feugiat vitae risus quis iaculis.

<div align="center"><img src="img/img-example-w5688-h3713.jpg" width=300 height=300><br><sub>Fig 1 - Aplication Deploy</sub></div>

#### <a name="chapter3part3"></a>Chapter 3 - Part 3: Simple Conditional Structure

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer accumsan id neque ut tempor. Nulla facilisi. Aliquam eu eros fermentum, commodo est sed, pharetra est. 
Curabitur lacinia blandit turpis rhoncus varius. Proin vulputate orci nulla, nec porttitor nibh consequat in. Suspendisse ac neque ut massa commodo auctor in sed libero. 
Sed tincidunt mauris eu tempor malesuada. Mauris feugiat vitae risus quis iaculis.

<div align="center"><img src="img/img-example-w5688-h3713.jpg" width=300 height=300><br><sub>Fig 1 - Aplication Deploy</sub></div>

#### <a name="chapter3part4"></a>Chapter 3 - Part 4: Compound Conditional Structure

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer accumsan id neque ut tempor. Nulla facilisi. Aliquam eu eros fermentum, commodo est sed, pharetra est. 
Curabitur lacinia blandit turpis rhoncus varius. Proin vulputate orci nulla, nec porttitor nibh consequat in. Suspendisse ac neque ut massa commodo auctor in sed libero. 
Sed tincidunt mauris eu tempor malesuada. Mauris feugiat vitae risus quis iaculis.

<div align="center"><img src="img/img-example-w5688-h3713.jpg" width=300 height=300><br><sub>Fig 1 - Aplication Deploy</sub></div>

#### <a name="chapter3part5"></a>Chapter 3 - Part 5: Chaining Conditional Structures

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer accumsan id neque ut tempor. Nulla facilisi. Aliquam eu eros fermentum, commodo est sed, pharetra est. 
Curabitur lacinia blandit turpis rhoncus varius. Proin vulputate orci nulla, nec porttitor nibh consequat in. Suspendisse ac neque ut massa commodo auctor in sed libero. 
Sed tincidunt mauris eu tempor malesuada. Mauris feugiat vitae risus quis iaculis.

<div align="center"><img src="img/img-example-w5688-h3713.jpg" width=300 height=300><br><sub>Fig 1 - Aplication Deploy</sub></div>

## <a name="chapter4"></a>Chapter 4: Repetitive Structures

#### <a name="chapter4part1"></a>Chapter 4 - Part 1: While Repetitive Structure

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer accumsan id neque ut tempor. Nulla facilisi. Aliquam eu eros fermentum, commodo est sed, pharetra est. 
Curabitur lacinia blandit turpis rhoncus varius. Proin vulputate orci nulla, nec porttitor nibh consequat in. Suspendisse ac neque ut massa commodo auctor in sed libero. 
Sed tincidunt mauris eu tempor malesuada. Mauris feugiat vitae risus quis iaculis.

<div align="center"><img src="img/img-example-w5688-h3713.jpg" width=300 height=300><br><sub>Fig 1 - Aplication Deploy</sub></div>

#### <a name="chapter4part2"></a>Chapter 4 - Part 2: For Repetitive Structure

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer accumsan id neque ut tempor. Nulla facilisi. Aliquam eu eros fermentum, commodo est sed, pharetra est. 
Curabitur lacinia blandit turpis rhoncus varius. Proin vulputate orci nulla, nec porttitor nibh consequat in. Suspendisse ac neque ut massa commodo auctor in sed libero. 
Sed tincidunt mauris eu tempor malesuada. Mauris feugiat vitae risus quis iaculis.

<div align="center"><img src="img/img-example-w5688-h3713.jpg" width=300 height=300><br><sub>Fig 1 - Aplication Deploy</sub></div>

## <a name="chapter5"></a>Chapter 5: Vectors

#### <a name="chapter5part1"></a>Chapter 5 - Part 1: Theory

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer accumsan id neque ut tempor. Nulla facilisi. Aliquam eu eros fermentum, commodo est sed, pharetra est. 
Curabitur lacinia blandit turpis rhoncus varius. Proin vulputate orci nulla, nec porttitor nibh consequat in. Suspendisse ac neque ut massa commodo auctor in sed libero. 
Sed tincidunt mauris eu tempor malesuada. Mauris feugiat vitae risus quis iaculis.

<div align="center"><img src="img/img-example-w5688-h3713.jpg" width=300 height=300><br><sub>Fig 1 - Aplication Deploy</sub></div>

#### <a name="chapter5part2"></a>Chapter 5 - Part 2: Declaration and Creation

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer accumsan id neque ut tempor. Nulla facilisi. Aliquam eu eros fermentum, commodo est sed, pharetra est. 
Curabitur lacinia blandit turpis rhoncus varius. Proin vulputate orci nulla, nec porttitor nibh consequat in. Suspendisse ac neque ut massa commodo auctor in sed libero. 
Sed tincidunt mauris eu tempor malesuada. Mauris feugiat vitae risus quis iaculis.

<div align="center"><img src="img/img-example-w5688-h3713.jpg" width=300 height=300><br><sub>Fig 1 - Aplication Deploy</sub></div>

#### <a name="chapter5part3"></a>Chapter 5 - Part 3: Access

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer accumsan id neque ut tempor. Nulla facilisi. Aliquam eu eros fermentum, commodo est sed, pharetra est. 
Curabitur lacinia blandit turpis rhoncus varius. Proin vulputate orci nulla, nec porttitor nibh consequat in. Suspendisse ac neque ut massa commodo auctor in sed libero. 
Sed tincidunt mauris eu tempor malesuada. Mauris feugiat vitae risus quis iaculis.

<div align="center"><img src="img/img-example-w5688-h3713.jpg" width=300 height=300><br><sub>Fig 1 - Aplication Deploy</sub></div>

## <a name="chapter6"></a>Chapter 6: Matrices

#### <a name="chapter6part1"></a>Chapter 6 - Part 1: Theory

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer accumsan id neque ut tempor. Nulla facilisi. Aliquam eu eros fermentum, commodo est sed, pharetra est. 
Curabitur lacinia blandit turpis rhoncus varius. Proin vulputate orci nulla, nec porttitor nibh consequat in. Suspendisse ac neque ut massa commodo auctor in sed libero. 
Sed tincidunt mauris eu tempor malesuada. Mauris feugiat vitae risus quis iaculis.

<div align="center"><img src="img/img-example-w5688-h3713.jpg" width=300 height=300><br><sub>Fig 1 - Aplication Deploy</sub></div>

#### <a name="chapter6part2"></a>Chapter 6 - Part 2: Declaration and Creation

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer accumsan id neque ut tempor. Nulla facilisi. Aliquam eu eros fermentum, commodo est sed, pharetra est. 
Curabitur lacinia blandit turpis rhoncus varius. Proin vulputate orci nulla, nec porttitor nibh consequat in. Suspendisse ac neque ut massa commodo auctor in sed libero. 
Sed tincidunt mauris eu tempor malesuada. Mauris feugiat vitae risus quis iaculis.

<div align="center"><img src="img/img-example-w5688-h3713.jpg" width=300 height=300><br><sub>Fig 1 - Aplication Deploy</sub></div>

#### <a name="chapter6part3"></a>Chapter 6 - Part 3: Access

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer accumsan id neque ut tempor. Nulla facilisi. Aliquam eu eros fermentum, commodo est sed, pharetra est. 
Curabitur lacinia blandit turpis rhoncus varius. Proin vulputate orci nulla, nec porttitor nibh consequat in. Suspendisse ac neque ut massa commodo auctor in sed libero. 
Sed tincidunt mauris eu tempor malesuada. Mauris feugiat vitae risus quis iaculis.

<div align="center"><img src="img/img-example-w5688-h3713.jpg" width=300 height=300><br><sub>Fig 1 - Aplication Deploy</sub></div>

# Usage <a name="usage"></a>

Use this space to show useful examples of how a project can be used. Additional screenshots, code examples and demos work well in this space. You may also link to more
resources.

_For more examples, please refer to the [Documentation](https://example.com)_

# Contributors <a name="contributors"></a>

| [<img src="https://github.com/vitorstabile.png" width=115 > <br> <sub> Vitor Garcia </sub>][github-url] | 
| :-----------------------------------------------------------------------------------------------------: |

# Contributing <a name="contributing"></a>

Contributions are what make the open source community such an amazing place to be learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

# Roadmap <a name="roadmap"></a>

See the [![Issues][issues-shield]][issues-url]  for a list of proposed features (and known issues).

# To Do <a name="todo"></a>

If so, list tasks / features that still need to be implemented in your application

:memo: To Do 1 

:memo: To Do 2

:memo: To Do 3 


# Contacts <a name="contacts"></a>

| Vitor Garcia                                     |
| :----------------------------------------------- |
| [![LinkedIn][linkedin-shield]][linkedin-url]     |
| [![Portfolio][portfolio-shield]][portfolio-url]  |
| [![GitHub][github-shield]][github-url]           |

# License <a name="License"></a>

- [![MIT License][license-shield]][license-url]

- Distributed under the MIT License. See `LICENSE` for more information.


<!-- README TUTORIALS -->

<!--

https://dev.to/reginadiana/como-escrever-um-readme-md-sensacional-no-github-4509

-->

<!-- 

Mark Down Guide - Readme Text Format Style

https://www.markdownguide.org/

-->

<!-- 

How to Create your Badges

https://gist.github.com/rupeshtiwari/8558ca0d8ec1c15619e4492dcd6aa81a

-->

<!-- USEFUL LINKS -->

<!--

Free Images Without Copyright

https://unsplash.com/


-->

<!-- MY BADGES -->

[project-shield]: https://img.shields.io/badge/link-project-green.svg
[project-url]: https://github.com/vitorstabile/logic-programming-in-c-basics
[linkedin-shield]: https://img.shields.io/badge/my-linkedin-blue.svg 
[linkedin-url]: https://www.linkedin.com/in/vitor-stabile-garcia-5b151b67
[portfolio-shield]: https://img.shields.io/badge/my-portfolio-red.svg
[portfolio-url]: https://vitorstabile.github.io
[github-shield]: https://img.shields.io/badge/my-github-green.svg
[github-url]: https://github.com/vitorstabile
[issues-shield]: https://img.shields.io/badge/link-issues-green.svg
[issues-url]: https://github.com/vitorstabile/logic-programming-in-c-basics/issues
[license-shield]: https://img.shields.io/badge/license-mit-blue.svg 
[license-url]: https://github.com/vitorstabile/logic-programming-in-c-basics/blob/master/LICENSE.txt
[logicalcourse-url]: https://www.udemy.com/course/curso-algoritmos-logica-de-programacao/
[devsuperior-url]: https://www.youtube.com/watch?v=PfYifUFmXk8
[wikibbok-url]: https://pt.wikibooks.org/wiki/Programar_em_C
[introduction-url]: https://github.com/vitorstabile/logic-programming-basics
[cormen-url]: https://www.amazon.com/Introduction-Algorithms-third-Thomas-Cormen-ebook/dp/B08FH8N996
