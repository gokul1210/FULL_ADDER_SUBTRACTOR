## NAME : GOKUL S

## REG NO : 212224230075


# FULL ADDER SUBTRACTOR

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

i)

![Screenshot 2025-04-21 215242](https://github.com/user-attachments/assets/8a486d29-2f22-404a-b724-c3d331222981)

ii)

![Screenshot 2025-04-21 215338](https://github.com/user-attachments/assets/026ce0d8-61b6-4d46-9137-09543b942e70)


**Procedure**

![procedure for dee](https://github.com/user-attachments/assets/87dcb498-b085-45b1-ab07-ea4aa1cd327c)


Program:**

i)FULL ADDER

![full adder](https://github.com/user-attachments/assets/995e48f0-0a13-4fe6-90a0-0a9161813e92)


ii)FULL SUBTRACTOR

![full sub 1](https://github.com/user-attachments/assets/30d8ecf3-df98-4634-813f-98dd0fb249b6)



**RTL Schematic**

## FULL ADDER

![full adder 1](https://github.com/user-attachments/assets/dde99a33-df43-4639-94a1-36d45c71c57b)

## full subtractor

![full sub 2](https://github.com/user-attachments/assets/7b90d707-e8b2-482a-b603-75ed61a37237)


**Output Timing Waveform**

## full adder

![full aadder2](https://github.com/user-attachments/assets/6bbe8781-3035-4cab-aded-870a1d7e3f9f)

## full subtractor

![full sub 3](https://github.com/user-attachments/assets/678285af-939a-4c32-ad58-57de866bec09)



**Result:**

Thus the Full Adder and Full Subtractor circuits are designed and the truth tables is verified using Quartus software.



