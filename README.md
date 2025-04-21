# FULL_ADDER_SUBTRACTOR
## NAME:VINOTH K R
## REG.NO:212224050060
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
FULL ADDER:
![Screenshot 2025-04-21 213543](https://github.com/user-attachments/assets/d0433194-cbad-4155-9cf9-42a8618102c2)
FULL SUBTRACT:
![19808ba79b68484396167b1cbc4b0819 1](https://github.com/user-attachments/assets/dfd94359-23f4-44fc-9b50-11595e78af9e)



**Procedure**

Write the detailed procedure here
![cffe3134f4494b628cd3b8bff680abd1 1](https://github.com/user-attachments/assets/edf94a33-5584-4ca9-8431-61f63acf6c4c)


**Program:**
FULL ADDER:
![92a880d78e604268b1f0541659ddb1e8 1](https://github.com/user-attachments/assets/1f23da92-0e09-4cf4-885a-c289faf286a9)
FULL SUBTRACT:
![e0f5072e39bf4ed38fac4920d70e996b 1](https://github.com/user-attachments/assets/a8e9a6af-3429-4004-8950-a2f73e1416fa)


**RTL Schematic**
FULL ADDER:
![697b117c33984f8f9d8d5e331294fe15 1](https://github.com/user-attachments/assets/f387192c-f8f4-42b0-bbac-fbf68b546eb8)
FULL SUBTRACT:
![697b117c33984f8f9d8d5e331294fe15 1](https://github.com/user-attachments/assets/88ca0b3b-1d21-438d-bea9-3c8ac60554d6)


**Output Timing Waveform**
FULL ADDER:
![7e64af4d6897410cb5cdddd944534f7c 1](https://github.com/user-attachments/assets/635b6c2e-354a-4e6d-8d0b-42095518c42a)
FULL SUBTRACT:
![b998299079704798a33e5b7d8d50c43c 1](https://github.com/user-attachments/assets/b8cf20f5-ef87-465c-a045-e8b3ff64f716)



**Result:**

Thus the Full Adder and Full Subtractor circuits are designed and the truth tables is verified using Quartus software.



