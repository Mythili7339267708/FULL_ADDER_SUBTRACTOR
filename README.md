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

**Procedure**

Write the detailed procedure here

**Program:**

/* Program to design a half subtractor and full subtractor circuit and verify its truth table in quartus using Verilog programming.

Developed by: V MYTHILI

RegisterNumber:212223040123
*/




**CODE:**




**FULL ADDER:**




<img width="293" alt="DE EX4 1" src="https://github.com/Mythili7339267708/FULL_ADDER_SUBTRACTOR/assets/144260246/172acb29-eeb2-43c5-b83e-6592c32a8d6c">





**FULL SUBTRACTOR:**




<img width="481" alt="DE EX 4 2" src="https://github.com/Mythili7339267708/FULL_ADDER_SUBTRACTOR/assets/144260246/bc99e3a5-dfad-4888-bbc4-b98f938a28d6">



**RTL Schematic**


**FULL ADDER:**


<img width="410" alt="DE EX 4 3" src="https://github.com/Mythili7339267708/FULL_ADDER_SUBTRACTOR/assets/144260246/dd2c1639-2ff2-4858-9617-6c1ba1512195">





**FULL SUBTRACTOR:**



<img width="353" alt="DE EX4 4" src="https://github.com/Mythili7339267708/FULL_ADDER_SUBTRACTOR/assets/144260246/5be82393-61b0-4f01-a199-f3a2b97f7089">




**Output Timing Waveform**



**FULL ADDER:**


<img width="590" alt="DE EX 4 5" src="https://github.com/Mythili7339267708/FULL_ADDER_SUBTRACTOR/assets/144260246/9a0d1799-926b-4dfa-9f6b-3f0b929f67e6">




**FULL SUBTRACTOR:**



<img width="586" alt="DE EX4 6" src="https://github.com/Mythili7339267708/FULL_ADDER_SUBTRACTOR/assets/144260246/667c99c3-169c-4922-af35-c59a271180b0">




**Result:**

Thus the Full Adder and Full Subtractor circuits are designed and the truth tables is verified using Quartus software.



