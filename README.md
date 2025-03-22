### study-of-basic-gates

**AIM:** 

To study and verify the truth table of logic gates in Quartus II using Verilog programming.

**Equipments Required:**

Software – Quartus prime 

**Theory**

Introduction Logic gates are the basic building blocks of any digital system. Logic gates are electronic circuits having one or more than one input and only one output. The relationship between the input and the output is based on a certain logic. Based on this, logic gates are named as

AND gate OR gate NOT gate NAND gate NOR gate Ex-OR gate Ex-NOR gate

**AND gate**

The AND gate is an electronic circuit that gives a high output (1) only if all its inputs are high. A dot (.) is used to show the AND operation i.e. A.B or can be written as AB
Y= A.B

**OR gate** 

The OR gate is an electronic circuit that gives a high output (1) if one or more of its inputs are high. A plus (+) is used to show the OR operation.
Y= A+B

**NOT gate**

The NOT gate is an electronic circuit that produces an inverted version of the input at its output. It is also known as an inverter. If the input variable is A, the inverted output is known as NOT A. This is also shown as A' or A with a bar over the top, as shown at the outputs.
Y= A'

**NAND gate**

This is a NOT-AND gate which is equal to an AND gate followed by a NOT gate. The outputs of all NAND gates are high if any of the inputs are low. The symbol is an AND gate with a small circle on the output. The small circle represents inversion.
Y= (AB)’

**NOR gate**

This is a NOT-OR gate which is equal to an OR gate followed by a NOT gate. The outputs of all NOR gates are low if any of the inputs are high. The symbol is an OR gate with a small circle on the output. The small circle represents inversion.
Y= (A+B)’

**Ex-OR gate**

The 'Exclusive-OR' gate is a circuit which will give a high output if either, but not both of its two inputs are high. An encircled plus sign (⊕) is used to show the Ex-OR operation.
Y= A⊕B

**Ex-NOR gate**

The 'Exclusive-NOR' gate circuit does the opposite to the EX-OR gate. It will give a low output if either, but not both of its two inputs are high. The symbol is an EX-OR gate with a small circle on the output. The small circle represents inversion.
Y= A⊕B

**Procedure** 

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**PROGRAM**

Program for logic gates and verify its truth table in quartus using Verilog programming

 Developed by: Sukirthana.M
 RegisterNumber: 212224220112
 ```
module EXP1(a,b,c,d,e,f,g,h);
input a,b;
output c,d,e,f,g,h;
assign c=a&b;
assign d=a|b;
assign e=a^b;
assign f=~(a&b);
assign g=~(a|b);
assign h=~(a^b);
endmodule
```
 
**Logic symbol & Truthtable**
AND GATE
![image](https://github.com/user-attachments/assets/484fb36e-a862-4378-b4fc-af8932370224)

OR GATE
![image](https://github.com/user-attachments/assets/551892dd-4f95-46a6-9092-7f337c92fdd2)

XOR GATE
![image](https://github.com/user-attachments/assets/f40a517c-3ad2-4916-98f5-3971f2936b3d)

NAND GATE 
![image](https://github.com/user-attachments/assets/0e5c902a-073c-4285-9ae6-fe3f9130f9f4)

NOR GATE
![image](https://github.com/user-attachments/assets/99a6ac6d-e5e4-4052-9b6a-b8236b1fdb7c)

XNOR GATE
![image](https://github.com/user-attachments/assets/9156ffd7-b556-4459-8a2e-b6ab6b10263b)



**RTL realization Output:** 
![Screenshot (55)](https://github.com/user-attachments/assets/371209d4-5703-4632-bc5c-ea21242b980b)


**RTL**
![Screenshot (58)](https://github.com/user-attachments/assets/c4074a06-8bbb-4916-88c0-2a84930dcea3)

**Result:**
        The program is verified and executed successfully.

