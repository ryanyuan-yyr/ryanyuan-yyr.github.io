---
layout: page
title: shell in rust
description: OSH course project -- write a shell in rust
img: assets/img/rust.jpg
importance: 1
category: Course projects
---

This project is a course project of Operating Systems(Honor), i.e., OSH. 

This is the first time that I learn how to write Rust. I spent 3 days to learn from scratch about the basic syntax and concepts in Rust, like ownership and lifetime, and 2 days to code up the shell. There is a steep learning curve for all beginners, I bet, even for proficient C++ programmers. 

I do appreciate how Rust manages to minimize the possibility of jeopardizing safty or performance. It has modern programming language features which are missing in C, and relatively simple syntax compared to C++. This project did prompt me to learn more about this programming language. 

In this project, I implemented some basic functions of shell along with pipe, I/O redirection(including I/O redirections based on file descriptors, here document and TCP I/O redirection) and shortcut(including ctrl+C sending SIGINT and ctrl+D sending EOF). 

The project can be found [here](https://github.com/ryanyuan-yyr/OSH-2021-Labs/tree/main/lab2), in the same repository with other labs in OSH. 