### NAME: S JUNAID SARDAR
### REG NO. 24003934
### EXP NO. 4 IMPLEMENTATION OF FULL ADDER SUBTRACTOR

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
**Full Adder:**
![391311483-481ae84f-c591-4522-aa7e-e69b9e9e163d](https://github.com/user-attachments/assets/655f8442-aa67-4e67-b6b6-9b343b62cf39)

**Full Subtractor**
![391311551-50636efd-b267-4a69-a6d3-be90f8119c97](https://github.com/user-attachments/assets/35084ba0-9536-499c-9731-4077d497b1a1)

**Program:**

![391311557-6faba0db-0bdc-4a53-8f91-96dfcb7ad815](https://github.com/user-attachments/assets/5c918e82-958f-46f2-a47d-ba1eba2333af)

**RTL Schematic**

![391311868-046c122c-49c4-4e1c-a5bb-6a5babc46f41](https://github.com/user-attachments/assets/d3613206-6871-4d97-8e52-9368743f1228)

**Output Timing Waveform**

![391311865-7603be5d-742b-46b1-b410-0662ed424ccf](https://github.com/user-attachments/assets/f074c4b9-f42f-4e02-9dd6-844674231380)

**Result:**

Thus the Full Adder and Full Subtractor circuits are designed and the truth tables is verified using Quartus software.



