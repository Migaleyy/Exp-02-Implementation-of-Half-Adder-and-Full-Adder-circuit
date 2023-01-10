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
/*
Program to design a half adder and full adder circuit and verify its truth table in quartus using Verilog programming.
Developed by: 
RegisterNumber:  22006541*/

Logic symbol & Truthtable

![logic-gates](https://user-images.githubusercontent.com/118262199/210506207-a0309d54-6b13-48db-81f2-eaedd9de51f6.jpg)

RTL realization

### Output:
### RTL
![image](https://user-images.githubusercontent.com/118262199/210506776-31a3416e-8f42-4276-b7ba-01763f99ba18.png)

![image](https://user-images.githubusercontent.com/118262199/210506812-5f050eae-bc25-4da2-9b0a-fc119b34a456.png)
### TIMING DIAGRAM
Half adder

![half adder exp 2](https://user-images.githubusercontent.com/118262199/211452203-77341df4-0ac4-4bf1-a2d8-8fc47c2748a4.png)

Full adder

![full adder exp 2](https://user-images.githubusercontent.com/118262199/211452231-640295dc-a391-43d2-8e88-2d1c017cacd2.png)


### TRUTH TABLE 

![truth table half adder'](https://user-images.githubusercontent.com/118262199/211452311-5d7cd5b4-cec5-4fa8-967c-58d6a34d44c2.png)

![truth table full adder](https://user-images.githubusercontent.com/118262199/211452317-004ef2d4-e6c7-43c0-9cd8-fbcf6b91d19c.png)

### Result:
Thus the different digital IC's are studied and the truth table for differnt logic gates are verified.


