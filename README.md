# CPU

In this project I used Logisim to implement a 32-bit two-cycle processor. I implemented all 32 registers promised by the MIPS ISA. My regfile is able to write to or read from any register specified in a given MIPS instruction without affecting any other registers. I created an Arithmetic Logic Unit (ALU) that supports all the operations needed by the instructions in our ISA. My CPU will support the instructions listed below:

![isa](https://user-images.githubusercontent.com/16792195/62587076-21d80380-b875-11e9-9f6d-8efd45315bb3.png)

The CPU has a 2-stage pipeline so that we are able to have instructions fetched from the instruction memory and then have it decoded, executed, and committed. The final CPU looks as follows when using Logisim:

