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

Developed by: Maha Vidya J P
RegisterNumber: 23013441 
*/
Logic symbol & Truthtable
RTL realization

## code

## Half Adder

![image](https://github.com/Mahavidyajp/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/144870914/fb9ecb3c-1f81-4400-811a-2ffac82c43a2)

## Full Adder

![image](https://github.com/Mahavidyajp/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/144870914/7efa041e-612b-46c8-9326-dd713ffcaced)

## Truth Table

## Half Adder

![image](https://github.com/Mahavidyajp/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/144870914/1e1fb604-9c8c-401f-9691-a270622c0cc6)

## Full Adder

![image](https://github.com/Mahavidyajp/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/144870914/9c155e0c-864e-4111-a8f1-cf55160eb69e)

## RTL

## Half Adder

![image](https://github.com/Mahavidyajp/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/144870914/30f2f563-63f4-475b-9719-dd713738b454)

## Full Adder

![image](https://github.com/Mahavidyajp/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/144870914/949c5dbe-152b-4b05-961b-66e27f990194)

## Timing Diagram

## Half Adder

![image](https://github.com/Mahavidyajp/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/144870914/8aebdbf8-b0f9-4628-9fdc-90efe3c5b3bd)

## Full Adder

![image](https://github.com/Mahavidyajp/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/144870914/05dddc45-6398-4e7f-a7ad-ed6142bd12e2)

### Result:
