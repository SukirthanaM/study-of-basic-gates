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
module EXP1(A,B,C,D,E,F,G,H);
input A,B;
output C,D,E,F,G,H;
assign C=A&B;
assign D=A|B;
assign E=A^B;
assign F=~(A&B);
assign G=~(A|B);
assign H=~(A^B);
endmodule
 ```
**Logic symbol & Truthtable**

AND GATE
![Screenshot 2025-03-22 204704](https://github.com/user-attachments/assets/5c4a438a-cd88-4257-b959-d813cd940fc3)

OR GATE
![Screenshot 2025-03-22 204825](https://github.com/user-attachments/assets/a36ff2a3-7a95-4c49-bd2a-569ab8b8302d)

XOR GATE
![Screenshot 2025-03-22 205000](https://github.com/user-attachments/assets/b02bede2-345e-4914-adc1-1426e4a661d5)

NAND GATE
![Screenshot 2025-03-22 210350](https://github.com/user-attachments/assets/f02b2be8-6637-4a48-8b31-a17b47ded54e)

NOR GATE
![Screenshot 2025-03-22 210452](https://github.com/user-attachments/assets/e65beeda-433f-42a1-a2e6-8480406267db)

XNOR GATE
![Screenshot 2025-03-22 210545](https://github.com/user-attachments/assets/53db2a6d-464a-41fa-a04c-f2238e02f09a)

**RTL realization Output:** 

**RTL**
![Screenshot (58)](https://github.com/user-attachments/assets/cf06252b-f3fc-4d01-a109-b8f63b68bb52)


**Result:**


