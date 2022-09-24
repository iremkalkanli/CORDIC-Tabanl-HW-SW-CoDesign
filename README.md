
# Cordic-based CoDesign
FPGA has programmable logic (PL) and processor system (PS). </br>
In this project, we developed a module in PL </br>
$${\sqrt{\sqrt{A^2+B^2}A*B} }$$ 
</br> with making this operation in PL we have much faster calculation, and in the PS part, the inputs of the operation are taken and processed in the PL part and the output is sent to the computer.
### Block Diagram of The System

![Block Diagram](https://github.com/iremkalkanli/CORDIC-Tabanl-HW-SW-CoDesign/blob/eaa24e9717b641f5aeaf121ef05d9a201fd76b30/Readme%20photos/codesign%20png.png)

  
## Results

The project was developed on the PYNQ Z2 development board with ZYNQ architecture. </br>
### PYNQ Z2

![PYNQ Z2](https://live.staticflickr.com/65535/47819083172_92655fe932_b.jpg)

The PS (Processor) section of ZYNQ is designed to feed the data to a special module to be designed and receive the result. </br>
Two number inputs are given and it is checked whether the expected output is the same. </br>
The numbers 10 and 20 are given. At the end of the calculation, the expected result of 14 was reached.

### The Output

![Output](https://github.com/iremkalkanli/CORDIC-Tabanl-HW-SW-CoDesign/blob/e0bcd10184291732d21ef3f248f848b527797755/Readme%20photos/output.png)
## Contributors
- [@ozlemcali](https://www.github.com/ozlemcali) design, development and documentation.

  
