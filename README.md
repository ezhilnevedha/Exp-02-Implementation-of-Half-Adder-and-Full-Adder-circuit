# Exp-03 Implementation of Half Adder and Full Adder circuit..

### Project By: Ezhil Nevedha.K
###   Register No:23007496


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

## Procedure:

Connect the supply (+5V) to the circuit
Switch ON the main switch
If the output is 1, then the led glows.

### Program:
/*
Program to design a half adder and full adder circuit and verify its truth table in quartus using Verilog programming.
## Half Adder Circuit:-

![Screenshot 2023-07-25 114634](https://github.com/ezhilnevedha/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/140057992/532fa728-6bb5-42cc-8a65-42f51168d653)


## Full Adder Circuit:-

![Screenshot 2023-07-25 192637](https://github.com/ezhilnevedha/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/140057992/10538e7e-c973-48cd-88fe-963f96102760)


*/
### Truthtable:-
   ## Half Adder Circuit:

   ![Screenshot 2023-07-25 112052](https://github.com/ezhilnevedha/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/140057992/0c0f05cd-5733-46da-837d-379c3f9a1549)


  ## Full Adder Circuit:-
   ![Screenshot 2023-07-26 112334](https://github.com/ezhilnevedha/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/140057992/ba0ac285-b749-4ed1-9820-73028d2d89f2)

  

*/
### RTL realization:
 ##  Half Adder Circuit:
   ![Screenshot 2023-07-25 111639](https://github.com/ezhilnevedha/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/140057992/b874e169-0e67-4caf-a1ac-95c49df6b103)

  

##   Full Adder Circuit:-
   
  ![Screenshot 2023-07-25 192601](https://github.com/ezhilnevedha/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/140057992/4d074713-5fc7-4a1f-9be5-2980d5762dbf)


### Output Waveform $ Timing Diagram:-
 ##  Half Adder Circuit:-
   ![Screenshot 2023-07-25 191009](https://github.com/ezhilnevedha/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/140057992/44e41540-7665-416b-ae6e-ea154741625b)

  
   
##   Full Adder Circuit:-
   ![Screenshot 2023-07-25 192958](https://github.com/ezhilnevedha/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/140057992/d053ea9e-a7b7-4191-a083-5d854b645392)

  

### Result:
To design a half adder and full adder circuit and verify its truth table in Quartus using Verilog programming.
