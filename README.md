**NAME:HARISH S**

**REG NO:24901078**

**EXP NO:4 FULL ADDER AND FULL SUBRACTOR**


# FULL_ADDER_SUBTRACTOR

Implementation-of-Full-Adder-and-Full-subtractor-circuit

**AIM:**

To design a Full Adder and Full Subtractor circuit and verify its truth table in Quartus using Verilog programming.

**EQUIPMENTS REQUIRED:**

Hardware – PCs, Cyclone II , USB flasher

Software – Quartus prime

**FULL ADDER AND FULL SUBRACTOR**

**FULL ADDER**

Full adder is a digital circuit used to calculate the sum of three binary bits. It consists of three inputs and two outputs. Two of the input variables, denoted by A and B, represent the two significant bits to be added. The third input, Cin, represents the carry from the previous lower significant position. Two outputs are necessary because the arithmetic sum of three binary digits ranges in value from 0 to 3, and binary 2 or 3 needs two digits. The two outputs are sum and carry.

Sum =A’B’Cin + A’BCin’ + ABCin + AB’Cin’ = A ⊕ B ⊕ Cin 

Carry = AB + ACin + BCin

![image](https://github.com/naavaneetha/FULL_ADDER_SUBTRACTOR/assets/154305477/0f30ba51-5ffb-4198-845f-18e054f675e7)

**Figure -1 FULL ADDER**

**FULL SUBRACTOR**

A full subtractor is a combinational circuit that performs subtraction involving three bits, namely minuend, subtrahend, and borrow-in . It accepts three inputs: minuend, subtrahend and a borrow bit and it produces two outputs: difference and borrow.

![image](https://github.com/naavaneetha/FULL_ADDER_SUBTRACTOR/assets/154305477/02b24f51-ab51-4304-9ad6-7b81ffc1ead5)

Diff = A ⊕ B ⊕ Bin 

Borrow out = A'Bin + A'B + BBin

**Truthtable**
**FULL ADDER**

![image](https://github.com/user-attachments/assets/74f06b74-90a2-4fb0-8fe0-bf90014e8ca8)



**FULL SUBRACTOR**

![image](https://github.com/user-attachments/assets/f367a031-cf85-4117-80a0-265dbe0a9eea)



**PROGRAM**

![image](https://github.com/user-attachments/assets/19f6f469-ae3f-46fc-a3dc-49e4b1c26d59)



**RTL VIEWER**

![image](https://github.com/user-attachments/assets/4086364e-c449-4a4a-960b-95681a9414a2)



**TIMING DIAGRAM**

![image](https://github.com/user-attachments/assets/2797deb9-2347-437f-b558-36db921136a7)



**RESULT**

Thus the Full Adder and Full Subtractor circuits are designed and the truth tables is verified using Quartus software.



