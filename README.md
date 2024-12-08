# FULL_ADDER_SUBTRACTOR

Implementation-of-Full-Adder-and-Full-subtractor-circuit

**AIM:**

To design a Full Adder and Full Subtractor circuit and verify its truth table in Quartus using Verilog programming.

**Equipments Required:**

Hardware – PCs, Cyclone II , USB flasher

Software – Quartus prime

**Full Adder and Full Subtractor**

**Full Adder**

Full adder is a digital circuit used to calculate the sum of three binary bits. It consists of three inputs and two outputs. Two of the input variables, denoted by A and B, represent the two significant bits to be added. The third input, Cin, represents the carry from the previous lower significant position. Two outputs are necessary because the arithmetic sum of three binary digits ranges in value from 0 to 3, and binary 2 or 3 needs two digits. The two outputs are sum and carry.

Sum =A’B’Cin + A’BCin’ + ABCin + AB’Cin’ = A ⊕ B ⊕ Cin 

Carry = AB + ACin + BCin

![image](https://github.com/naavaneetha/FULL_ADDER_SUBTRACTOR/assets/154305477/0f30ba51-5ffb-4198-845f-18e054f675e7)

**Figure -1 FULL ADDER**

**Full Subtractor**

A full subtractor is a combinational circuit that performs subtraction involving three bits, namely minuend, subtrahend, and borrow-in . It accepts three inputs: minuend, subtrahend and a borrow bit and it produces two outputs: difference and borrow.

![image](https://github.com/naavaneetha/FULL_ADDER_SUBTRACTOR/assets/154305477/02b24f51-ab51-4304-9ad6-7b81ffc1ead5)

Diff = A ⊕ B ⊕ Bin 

Borrow out = A'Bin + A'B + BBin

**Truthtable**
![WhatsApp Image 2024-12-09 at 01 44 51_e9c6f9a9](https://github.com/user-attachments/assets/22eb3148-9f70-47e3-a77d-0deb51dbb502)


**Procedure**

Write the detailed procedure here
1.Type the program in quartus software.
2.Compile and run the program.
3.Generate the RTL schematic and save the logic diagram.
4.Create notes for inputs and outputs to generate the timing diagram.
5.For different input combinations generate the timing diagram.

**Program:**

/* Program to design a half subtractor and full subtractor circuit and verify its truth table in quartus using Verilog programming. 
![Screenshot 2024-12-09 014335](https://github.com/user-attachments/assets/30f92c3a-8154-4d02-91f8-1900180b18ba)

Developed by: Kowshika.R RegisterNumber:24001226
*/

**RTL Schematic**
![WhatsApp Image 2024-12-09 at 01 49 03_35dbca18](https://github.com/user-attachments/assets/a9e74924-9f2f-43b3-b7f2-6fc78ca6d6ac)


**Output Timing Waveform**
![WhatsApp Image 2024-12-09 at 01 34 50_333376f5](https://github.com/user-attachments/assets/93f693f1-7566-44b6-8515-9a60e79d4adf)


**Result:**

Thus the Full Adder and Full Subtractor circuits are designed and the truth tables is verified using Quartus software.



