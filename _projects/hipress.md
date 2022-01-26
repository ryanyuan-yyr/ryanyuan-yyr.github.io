---
layout: page
title: Extension of CompLL
description: CompLL is a compiler for a DSL that aims to help practitioners to easily implement highly-opitimized gradient compression algorithms used in DNN training. 
img: assets/img/hipress.JPEG
importance: 1
category: Research projects
---

This project (or, followup) is to extend the syntax of a DSL and modify the current compiler implementation to support more algorithms that can be implemented with this DSL. 

The project is a follow-up study of [this project](https://www.ruichuan.org/papers/hipress-sosp21.pdf). The goal of `CompLL` is to ease the practitioners from the difficulties of coding a highly proficient gradient algorithm. 

CompLL provides a unified API abstraction for implementing gradient compression algorithms. It has two simple APIs: encode and decode, as well as a few algorithm-specific parameters (e.g., compression
rate for sparsification, and bitwidth or precision for quantization). The encode API takes as input a gradient matrix and generates a compressed gradient as output. In particular, we use uint8 as the type of the output matrix, because we can then cast one or multiple uint8 to any type in CUDA. On the other hand, the decode API unfolds a compressed gradient into its original form.

In the publication above, you can find an implementation of `TernGrad` using this specific DSL. However, the syntax supported is still limited to implement some sophisticated algorithms. 

Currently, I am modifying the compiler to implement `3-LC`, a relatively complex gradient compression/decompression algorihm. 

The source code of this project can be accessed [here](https://gitlab.com/hipress/hipress). 