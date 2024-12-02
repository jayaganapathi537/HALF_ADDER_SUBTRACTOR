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

![Screenshot 2024-12-02 112243](https://github.com/user-attachments/assets/9cb74947-9b2c-4a3c-827f-a63370b418bf)


Figure -01 HALF ADDER

**Half Subtractor**

The half-subtractor is a combinational circuit which is used to perform subtraction of two bits. It has two inputs, X (minuend) and Y (subtrahend) and two outputs D (difference) and B (borrow). To perform x - y, we have to check the relative magnitudes of x and y. If x ;;, y, we have three possibilities: 0 - 0 = 0, 1 - 0 = 1, and 1 - I = 0. The result is called the difference bit. If x < y, we have 0 - I, and it is necessary to borrow a 1 from the next higher stage. The I borrowed from the next higher stage adds 2 to the minuend bit, just as in the decimal system a borrow adds 10 to a minuend digit. With the minuend equal to 2, the difference becomes 2 - I = 1. The half-subtractor needs two outputs. One output generates the difference and will be designated by the symbol D. The second output, designated B for borrow, generates the binary signal that informs the next stage that a I has been borrowed. 

Diff = A’B+AB’ =A ⊕ B
Borrow = A’B

![Screenshot 2024-12-02 112804](https://github.com/user-attachments/assets/fea1f54c-e525-4d60-86c4-a9d52a028843)


Figure -02 HALF Subtractor

**Truthtable**
**HALF ADDER**
![Screenshot 2024-12-02 112948](https://github.com/user-attachments/assets/e7ae864e-a87f-40a8-b194-283502a52687)

**HALF SUBTRACTOR**
![Screenshot 2024-12-02 112956](https://github.com/user-attachments/assets/70fb72d8-36ef-4024-a99d-13ffabb6026f)

**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**

/* Program to design a half adder and full adder circuit and verify its truth table in quartus using Verilog programming.

**HALF ADDER**
![Screenshot 2024-12-02 111154](https://github.com/user-attachments/assets/98259253-121f-4f43-8cb6-94b7fd3818b8)

**HALF SUBTRACTOR**

![Screenshot 2024-12-02 112721](https://github.com/user-attachments/assets/18e53af9-5635-4f8c-97ee-05453a1d08a6)

**Developed by: JAYAGANAPATHI S**
**RegisterNumber: 24900059**

**RTL Schematic**
**HALF ADDER**
![Screenshot 2024-12-02 112243](https://github.com/user-attachments/assets/9610f39a-b4b9-4c13-a11b-6f1c1867b057)
**HALF SUBTRACTOR**
![Screenshot 2024-12-02 112804](https://github.com/user-attachments/assets/42037d98-6b1c-4da0-b11d-53b0aa8357ee)


**Output/TIMING Waveform**
![Screenshot 2024-12-02 113514](https://github.com/user-attachments/assets/95b2386e-1950-467a-91cc-722266a1fcb5)

![Screenshot 2024-12-02 113526](https://github.com/user-attachments/assets/5d129b81-9b29-466f-af34-86ee488ddc3e)

**Result:**
 Thus designed a half adder and half subtractor circuit and verified its truth table in Quartus using Verilog programming.
