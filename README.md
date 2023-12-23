# Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit

# Implementation-of-Half-Adder-and-Full-Adder-circuit
### AIM:
To design a half adder and full adder circuit and verify its truth table in Quartus using Verilog programming.

### Equipments Required:
Hardware – PCs, Cyclone II , USB flasher
Software – Quartus prime
Theory
Adders are digital circuits that carry out addition of numbers.

### Half Adder
Half adder is a combinational circuit that performs simple addition of two binary numbers. The input variables designate the augend and addend bits; the output variables produce the sum and carry. It is necessary to specify two output variables because the result may consist of two binary digits.

Sum = A’B+AB’ =A ⊕ B Carry = AB

### Full Adder
Full adder is a digital circuit used to calculate the sum of three binary bits. It consists of three inputs and two outputs. Two of the input variables, denoted by A and B, represent the two significant bits to be added. The third input, Cin, represents the carry from the previous lower significant position. Two outputs are necessary because the arithmetic sum of three binary digits ranges in value from 0 to 3, and binary 2 or 3 needs two digits. The two outputs are sum and carry.

Sum =A’B’Cin + A’BCin’ + ABCin + AB’Cin’ = A ⊕ B ⊕ Cin Carry = AB + ACin + BCin

 ![image](https://user-images.githubusercontent.com/36288975/163552156-a13e5a56-c638-4110-97d9-8896907c8d25.png)

#### Figure -01 HALF ADDER 


![image](https://user-images.githubusercontent.com/36288975/163552057-b3547877-6d07-45b4-b7e0-bcfebfad9e1d.png)

#### Figure -02 FULL ADDER 

### Procedure

Connect the supply (+5V) to the circuit
Switch ON the main switch
If the output is 1, then the led glows.
### 
Program:
HALF ADDER



![image](https://github.com/vasanthkumarch/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/147473403/01287726-638b-4175-880f-910946fe5b2c)




FULL ADDER




![image](https://github.com/vasanthkumarch/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/147473403/05808bc4-8b6c-4f6a-b5ef-bd23f044575d)






/*
Program to design a half adder and full adder circuit and verify its truth table in quartus using Verilog programming.
Developed by:MURALIDHARAN M
RegisterNumber:23012704
*/
Logic symbol & Truthtable
HALF ADDER



![image](https://github.com/vasanthkumarch/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/147473403/627be428-d984-4a16-866c-1af75811235d)




FULL ADDER



![image](https://github.com/vasanthkumarch/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/147473403/e1a41bfd-e5cf-4486-9bd3-13507f9c3084)






RTL realization
Half Adder Circuit:



![image](https://github.com/vasanthkumarch/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/147473403/e697cc1c-752f-4f2f-9a76-7fc852bdd51f)




Full Adder Circuit:



![image](https://github.com/vasanthkumarch/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/147473403/c94caef9-ef69-472d-aceb-a3c0bc9f07d6)







### Output:
### RTL
### TIMING DIAGRAM
Half Adder Diagram:



![image](https://github.com/vasanthkumarch/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/147473403/5f3c37ae-4ac6-4475-8073-c572e06a459c)




Full Adder Diagram:




![image](https://github.com/vasanthkumarch/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/147473403/78a6d3be-7b8a-48f9-a361-c93b1c35b6ee)






### TRUTH TABLE 

### Result:
To design a half adder and full adder circuit and verify its truth table in Quartus using Verilog programming.
