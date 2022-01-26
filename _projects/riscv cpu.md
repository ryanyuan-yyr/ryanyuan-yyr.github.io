---
layout: page
title: RISC-V CPU on FPGA
description: A 5-stage-pipelined RISC-V CPU implemented on FPGA
img: assets/img/riscv.jpg
importance: 1
category: Course projects
---

This project is a course project in Computer Organization and Design. 

In this project, we implemented a 5-stage-pipelined RISC-V CPU on FPGA, by writing Verilog code, perform stimulation & synthesis on Vivado and program on an FPGA development board.  

The project has 6 phases: 
1. Lab1: ALU
2. Lab2: Registers and memories
3. Lab3: How to write RISCV assembly codes
4. Lab4: Single cycle CPU design
5. Lab5: 5-stage-pipelined CPU design
6. Lab6: A capstone lab. The students were asked to implement whatever they want based on the framework of the previous projects. I implemented `ecall`(by which I am allowed to display digits and control LED lights on the development board) and interrupts based on lab5. 

The project can be found [here](https://github.com/ryanyuan-yyr/COD-Labs). 