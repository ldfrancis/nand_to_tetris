# nand_to_tetris [Course]
Designing a general purpose computer from the ground up. Based on the coursera course, [Build a Modern Computer from First Principles: From Nand to Tetris (Project-Centered Course)](https://www.coursera.org/learn/build-a-computer/home/welcome)

This repository contains the implementations for the concepts discussed in the course, consisting of a hardware (the HACK computer) and a software hierarchy that runs a tetris application. The hardware is developed in a hardware simulator. This project is divided into two parts, according to the course. The first part focuses on building the hardware while the second part focuses on the software. Inspired by the project's name, nand_to_tetris, the first part is named nand_to_hack and the second part, hack_to_tetris.

## nand_to_hack
nand_to_hack involves designing a computer hardware from the ground up starting with a nand gate. The nand gate chip is used to build all other chips required to design the 'hack' computer. This chips are designed using a hardware simulator that can be [downloaded here](https://www.nand2tetris.org/software).
### Project 1: Boolean logic [[description](https://www.nand2tetris.org/project01)]
This first project involves the design of all Chips described in chapter 1 of the textbook by using only primitive nand gates. The chips and their implementation links to their implementation in .hdl (hardware definition language) are listed in the table below:
Chip Name | Description| Design(in .hdl) 
--- | --- | --- 
Not | Not gate | . 
And | And gate | . 
Or | Or gate | . 
Xor | Xor gate | . 
Mux | Mux gate | . 
DMux | DMux gate | . 
Not16 | 16bit Not | . 
And16 | 16bit And | . 
Or16 | 16bit Or | . 
Mux16 | 16bit multiplexor | . 
Or8Way | Or(in0,in1,...,in7) | . 
Mux4Way16 | 16-bit/4-way mux | . 
Mux8Way16 |16-bit/8-way mux | . 
DMux4Way | 4-way demultiplexor | . 
DMux8Way | 8-way demultiplexor | . 
