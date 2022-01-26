---
layout: page
title: cminusf compiler
description: A compiler frontend for a C-like language
img: assets/img/cminusf.jpg
importance: 1
category: Course projects
---

`cminusf` is an education-oriented, C-like programming language that the instructor used in course Compilers Principles. It supports most of the syntax in C and a large portion of it is compactible with C or C++. 

The project is divided in 5 stages: 
1. Lab1: Lexical analysis(implemented with `lexer`) and syntatical analysis(implemented with `bison`)
1. Lab2: Getting familiar with LLVM IR and how to use IR builder to facilitate the IR generation progress. 
1. Lab3: Implemented the translation progress, that is, generation of LLVM IR by traversing the AST. 
1. Lab4: Machine independent optimization. We implemented several optimization passes, including constant propagation, live variable analysis and loop constant hoist. 
1. Lab5: This phase is optional according to the curriculum syllabus. I decided to extend the language features of `cminusf`. 
   Within a week, I rendered the compiler to support structures, pointers, arrays, member functions, operator overloading and class templates. 

Detailed stipulation of the 5 stages can be found [here](https://github.com/ryanyuan-yyr/2021fall-compiler_cminus/tree/main/Documentations). 

Click [here](https://github.com/ryanyuan-yyr/2021fall-compiler_cminus) to have full access to the project source code and reports. 