
**AIM:**

To implement the given logic function verify its operation in Quartus using Verilog programming.

F1= A’B’C’D’+AC’D’+B’CD’+A’BCD+BC’D 

F2=xy’z+x’y’z+w’xy+wx’y+wxy

**Equipment Required:**

Hardware – PCs, Cyclone II , USB flasher

**Software – Quartus prime**

**Theory**

**Logic Diagram**

**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Truth Table**

![exp2)truth table](https://github.com/user-attachments/assets/c450773b-7374-41e4-9e16-7b308cad11f1)


**Minimization**

1)F1

![WhatsApp Image 2024-12-23 at 19 41 09_0b6cd299](https://github.com/user-attachments/assets/001aaaa5-e6b2-4275-af1c-5ef7e437f54e)

F2)

![WhatsApp Image 2024-12-23 at 19 43 13_e37d0a00](https://github.com/user-attachments/assets/17bde640-bc89-416c-856a-7a90ad10fd37)


**Program:**

/* Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 

Developed by:Harshana M V

RegisterNumber:24002128

i)
module funct1(a,b,c,d,f1);

input a,b,c,d;

output f1;

assign f1=((~b & ~d)|(~a & b & d)|(a & b & ~c));

endmodule

ii)
module funct2(w,x,y,z,f2);

input w,x,y,z;

output f2;

assign f2=((~y & z)|( w & y )|(x & y));

endmodule



**RTL**
1)F1

![exp2rtl1](https://github.com/user-attachments/assets/d89160dc-2170-42d4-9064-ce2be8dcb218)

2)F2

![exp2)rtl2](https://github.com/user-attachments/assets/0a71d048-d1b8-4101-8d40-550849fd5217)



**Output:**
1)F1

![exp2)op1](https://github.com/user-attachments/assets/3a055165-f67c-4c22-a413-e70ebedb3b58)

2)F2

![exp2)op2](https://github.com/user-attachments/assets/b52508d6-066f-4ccc-8837-1ab74ea7f45e)


**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

