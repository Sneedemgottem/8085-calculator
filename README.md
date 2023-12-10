# 8085-calculator
Breadboard Computer using Intel 8085 CPU.

TODO: Post verilog code for FPGA as well as minimal operating system written in assembly. Also post picture of schematic.

**Image 1:** Breadboard overview.
* cy7c128a RAM module
* Nand chip
* AT28C256 ROM
* 8085 CPU
* Aartix-7 FPGA
* and level shifters from 3.3v to 5v and vice versa. Reason is: fpga takes 3.3v and all computer components run at 5.

![alt text](https://github.com/Sneedemgottem/8085-calculator/raw/master/breadboard.jpg "breadboard.jpg")

**Image 2:** TM1638 module connected to FPGA
Needed to use FPGA in order to interface with the tm1638. Has a serial connection and weird timing.
![alt text](https://github.com/Sneedemgottem/8085-calculator/raw/master/tm1638.jpg "tm1638.jpg")
