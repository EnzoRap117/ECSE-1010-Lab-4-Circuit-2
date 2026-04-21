<!---

This file is used to generate your project datasheet. Please fill in the information below and delete any unused
sections.

You can also include images in this folder and reference them in the markdown. Each image must be less than
512 kb in size, and the combined size of all images must be less than 1 MB.
-->

## How it works

This project uses a series of NAND gates to store values Q0 and Q1 that can only be changed by the inputs S and R if the enable pin is active.

## How to test
To use the circuit, supply voltage to the enable pin to allow write access and supply voltage to either the S or R inputs to change the values of Q0 and Q1.
The following table shows how the circuit should function, each line should be viewed as one step in sequence.

| S | R | E | Q0 | Q1 |
|:---:|:---:|:---:|:---:|:---:|
| 0 | 0 | 0 | 0 | 0 |
| 1 | 0 | 0 | 0 | 0 |
| 1 | 0 | 1 | 1 | 0 |
| 0 | 0 | 1 | 1 | 0 |
| 0 | 0 | 0 | 1 | 0 |
| 0 | 1 | 1 | 1 | 1 |
| 0 | 0 | 0 | 1 | 1 |
  
## External hardware

List external hardware used in your project (e.g. PMOD, LED display, etc), if any
