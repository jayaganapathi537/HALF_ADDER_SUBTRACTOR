# HALF_ADDER_SUBTRACTOR

Implementation-of-Half-Adder-and-Half Subtractor-circuit

**AIM:**

To design a half adder and half subtractor circuit and verify its truth table in Quartus using Verilog programming.

**Equipments Required:**

Hardware – PCs, Cyclone II , USB flasher 

Software – Quartus prime Theory Adders are digital circuits that carry out the addition of numbers.

**Half Adder**

Half adder is a combinational circuit that performs simple addition of two binary numbers. The input variables designate the augend and addend bits; the output variables produce the sum and carry. It is necessary to specify two output variables because the result may consist of two binary digits.

Sum = A’B+AB’ =A ⊕ B Carry = AB

![image](https://github.com/naavaneetha/HALF_ADDER_SUBTRACTOR/assets/154305477/bd4a0b2c-cdbc-4184-ab08-81578f121e1f)

Figure -01 HALF ADDER

**Half Subtractor**

The half-subtractor is a combinational circuit which is used to perform subtraction of two bits. It has two inputs, X (minuend) and Y (subtrahend) and two outputs D (difference) and B (borrow). To perform x - y, we have to check the relative magnitudes of x and y. If x ;;, y, we have three possibilities: 0 - 0 = 0, 1 - 0 = 1, and 1 - I = 0. The result is called the difference bit. If x < y, we have 0 - I, and it is necessary to borrow a 1 from the next higher stage. The I borrowed from the next higher stage adds 2 to the minuend bit, just as in the decimal system a borrow adds 10 to a minuend digit. With the minuend equal to 2, the difference becomes 2 - I = 1. The half-subtractor needs two outputs. One output generates the difference and will be designated by the symbol D. The second output, designated B for borrow, generates the binary signal that informs the next stage that a I has been borrowed. 

Diff = A’B+AB’ =A ⊕ B
Borrow = A’B

 ![image](https://github.com/naavaneetha/HALF_ADDER_SUBTRACTOR/assets/154305477/d76b099c-513f-4e7c-843a-e2fd028a531a)

Figure -02 HALF Subtractor

**Truthtable**

![371469372-f8ab0420-6e66-4438-984b-f0df3654f690](https://github.com/user-attachments/assets/5ebcb1d4-32ad-471b-a0e7-8677d5c762ca)

**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**

/* Program to design a half adder and full adder circuit and verify its truth table in quartus using Verilog programming.

**Developed by: JAYAGANAPATHI S 
  RegisterNumber: 24900059**
  
**HALF ADDER**

![Screenshot 2024-12-02 111154](https://github.com/user-attachments/assets/8c277f16-b3ab-48f5-ae08-81049e08d7f9)

**HALF SUBTRACTOR**

![Screenshot 2024-12-02 112721](https://github.com/user-attachments/assets/ba04c64e-b51e-4ec1-8ca5-0e9c60efcdfd)

**RTL Schematic**

**HALF ADDER**

![Screenshot 2024-12-02 112243](https://github.com/user-attachments/assets/965ff91c-5dc5-4ae5-90f0-474c61eb124e)
**HALF SUBTRACTOR**

![Screenshot 2024-12-02 112804](https://github.com/user-attachments/assets/585de814-9e6a-4b54-86b5-d0a2b1ba008f)

**Output/TIMING Waveform**

**HALF ADDER**

![Screenshot 2024-12-02 113514](https://github.com/user-attachments/assets/716cc80e-e5f0-4405-8a16-95e258aae12e)
**HALF SUBTRACTOR**

![Screenshot 2024-12-02 113526](https://github.com/user-attachments/assets/f81a85f5-8334-42a8-8748-d7f0c90535ee)

**Result:**

Thus the design of a half adder and half subtractor circuit using Verilog programming had been successfully verified.
