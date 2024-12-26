### NAME:SUDARSAN.A
### REG NO:24900190
### EXP NO 3:IMPLEMENTATION-OF-HALF-ADDER-AND-HALF SUBTRACTOR-CIRCUIT

### AIM:

To design a half adder and half subtractor circuit and verify its truth table in Quartus using Verilog programming.

### Equipments Required:

Hardware – PCs, Cyclone II , USB flasher 

Software – Quartus prime Theory Adders are digital circuits that carry out the addition of numbers.

### Half Adder

Half adder is a combinational circuit that performs simple addition of two binary numbers. The input variables designate the augend and addend bits; the output variables produce the sum and carry. It is necessary to specify two output variables because the result may consist of two binary digits.

Sum = A’B+AB’ =A ⊕ B Carry = AB

![image](https://github.com/naavaneetha/HALF_ADDER_SUBTRACTOR/assets/154305477/bd4a0b2c-cdbc-4184-ab08-81578f121e1f)

Figure -01 HALF ADDER

### Half Subtractor

The half-subtractor is a combinational circuit which is used to perform subtraction of two bits. It has two inputs, X (minuend) and Y (subtrahend) and two outputs D (difference) and B (borrow). To perform x - y, we have to check the relative magnitudes of x and y. If x ;;, y, we have three possibilities: 0 - 0 = 0, 1 - 0 = 1, and 1 - I = 0. The result is called the difference bit. If x < y, we have 0 - I, and it is necessary to borrow a 1 from the next higher stage. The I borrowed from the next higher stage adds 2 to the minuend bit, just as in the decimal system a borrow adds 10 to a minuend digit. With the minuend equal to 2, the difference becomes 2 - I = 1. The half-subtractor needs two outputs. One output generates the difference and will be designated by the symbol D. The second output, designated B for borrow, generates the binary signal that informs the next stage that a I has been borrowed. 

Diff = A’B+AB’ =A ⊕ B
Borrow = A’B

 ![image](https://github.com/naavaneetha/HALF_ADDER_SUBTRACTOR/assets/154305477/d76b099c-513f-4e7c-843a-e2fd028a531a)

Figure -02 HALF Subtractor

### Truthtable
![Screenshot 2024-11-28 114052](https://github.com/user-attachments/assets/0098b00d-19dd-4c5a-ac53-a18235526738)

![Screenshot 2024-11-28 114117](https://github.com/user-attachments/assets/46845cc7-7bc2-4cf9-906b-7e4d4e38ca1a)

### Procedure

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


### Program:
![Screenshot 2024-11-28 113035](https://github.com/user-attachments/assets/5adb2916-5000-40ff-b9a6-70616e23b087)


### RTL Schematic
![Screenshot 2024-11-28 110502](https://github.com/user-attachments/assets/5a21f6b7-135e-4f3b-9d9d-9e883fa6348c)


### Output/TIMING Waveform

 ![Screenshot 2024-11-28 112140](https://github.com/user-attachments/assets/ae7b3cfb-f438-46b5-b676-3318e0d396f0)


### Result:
Implementation-of-Half-Adder-and-Half Subtractor-circuit is successfully implemented qnd verified.
