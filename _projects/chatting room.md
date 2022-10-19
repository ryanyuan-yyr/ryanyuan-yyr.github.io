---
layout: page
title: Chatting Group
description: OSH course project -- A chatting group that connects everyone
img: assets/img/chatting.jpg
importance: 1
category: Course projects
---

This project is a course project of Operating Systems(Honor), i.e., OSH. 

In this project, we need to implement a group chatting program that forward the message from each person to everyone else. The program is implemented in 2 versions: 
1. Using mutithread
For each client(that is, a person in the chatting group), an exlusive thread is made to receive messages from everyone else as well as sending the message from this client to others. 

2. Using `select`
>  `select()`  and `pselect()` allow a program to monitor multiple file descriptors, waiting until one or more of the file descriptors become "ready" for some class of I/O operation (e.g., input possible).

By using `select`, multi-thread programming is not need. 

The project can be found [here](https://github.com/ryanyuan-yyr/OSH-2021-Labs/tree/main/lab3). 