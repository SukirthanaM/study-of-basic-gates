### study of basic gates

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

1.	Type the program in Quartus software .

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**PROGRAM**

Program for logic gates and verify its truth table in quartus using Verilog programming

** Developed by: A.Nabithra **

** RegisterNumber: 212224230172 **


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

![image](https://github.com/user-attachments/assets/0c993bac-763f-48d7-a058-bf41ac496ec3)
![image](https://github.com/user-attachments/assets/f65e825b-42da-4219-a8f8-f3576a926adc)
![image](https://github.com/user-attachments/assets/1071c051-c53e-4588-a4a5-0a9b4bd828d4)

![image](https://github.com/user-attachments/assets/6c45f174-284a-48c4-823e-d5f808ccf9e9)
![image](https://github.com/user-attachments/assets/9b658a19-1319-464f-8182-9bff57b86b94)
![image](https://github.com/user-attachments/assets/42f533cd-c9f5-496e-bcca-48dae59032ab)


**RTL realization Output:** 
![image](https://github.com/user-attachments/assets/fec70944-c754-4c21-a35e-d68693f48ee6)


**RTL**
![image](https://github.com/user-attachments/assets/45137270-5069-4ecf-9386-b0ed749c0d30)

**Result:**

Thus, the Program is verified and executed successfully.


