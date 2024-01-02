# Experiment--03-Half-Subtractor-and-Full-subtractor
## Implementation-of-Half-subtractor-and-Full-subtractor-circuit
## AIM:
To design a half subtractor and full subtractor circuit and verify its truth table in Quartus using Verilog programming.

## Equipments Required:
## Hardware – PCs, Cyclone II , USB flasher
## Software – Quartus prime
## Theory
Subtractor circuits take two binary numbers as input and subtract one binary number input from the other binary number input. Similar to adders, it gives out two outputs, difference and borrow (carry-in the case of Adder). There are two types of subtractors.

## Half Subtractor Full Subtractor
## Half Subtractor
The half-subtractor is a combinational circuit which is used to perform subtraction of two bits. It has two inputs, X (minuend) and Y (subtrahend) and two outputs D (difference) and B (borrow). To perform x - y, we have to check the relative magnitudes of x and y. If x ;;, y, we have three possibilities: 0 - 0 = 0, 1 - 0 = 1, and 1 - I = 0. The result is called the difference bit. If x < y, we have 0 - I, and it is necessary to borrow a 1 from the next higher stage. The I borrowed from the next higher stage adds 2 to the minuend bit, just as in the decimal system a borrow adds 10 to a minuend digit. With the minuend equal to 2, the difference becomes 2 - I = 1. The half-subtractor needs two outputs. One output generates the difference and will be designated by the symbol D. The second output, designated B for borrow, generates the binary signal that informs the next stage that a I has been borrowed.
![half-subtractor9](https://user-images.githubusercontent.com/36288975/166112538-58c3bc7c-ee5d-4e6a-ac8d-8e8328efe27a.png)


Sum = X'Y+XY' = X ⊕ Y
Carry=X'Y

## Full Subtractor
A full subtractor is a combinational circuit that performs subtraction involving three bits, namely minuend, subtrahend, and borrow-in . It accepts three inputs: minuend, subtrahend and a borrow bit and it produces two outputs: difference and borrow. 
![full-subtractor6](https://user-images.githubusercontent.com/36288975/166112541-24c68359-3de8-4674-ae22-8272ffc385ed.png)


Diff = A ⊕ B ⊕ Bin B = A'Bin + A'B + BBin

## Procedure



Write the detailed procedure here 


## Program:
##Halfsubractor:
![Screenshot 2024-01-02 041046](https://github.com/Nandy-nan/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/153698914/35879c7f-d449-46c9-af25-9e1c0ee68cca)

##Full subractor:
![Screenshot 2024-01-02 041055](https://github.com/Nandy-nan/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/153698914/19cf4575-a2a5-4d38-9650-d00c8cdd88f3)


##RTL:

![Screenshot 2024-01-02 041118](https://github.com/Nandy-nan/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/153698914/b6d688fa-c73c-4078-a324-54b67c43d073)

![Screenshot 2024-01-02 041126](https://github.com/Nandy-nan/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/153698914/fff45b3c-160e-4f8c-8653-49d05b4d7568)



##Truthtable:
![Screenshot 2024-01-02 041103](https://github.com/Nandy-nan/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/153698914/e68de7e7-5c41-47a8-a70a-db404bd53a71)

![Screenshot 2024-01-02 041110](https://github.com/Nandy-nan/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/153698914/1ed9ce9c-9fd4-4876-a8c2-3c6d2a82a725)










/*
Program to design a half subtractor and full subtractor circuit and verify its truth table in quartus using Verilog programming.
Developed by: R.Nandhana
RegisterNumber:23005507  
*/

## Output:

![Screenshot 2024-01-02 041138](https://github.com/Nandy-nan/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/153698914/c16f457b-b7cb-4e59-94b4-02310d772060)

![Screenshot 2024-01-02 041147](https://github.com/Nandy-nan/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/153698914/41b77d44-b927-4a2b-96e6-061a39dd35a1)







## Result:
Thus the half subtractor and full subtractor circuits are designed and the truth tables is verified using quartus software.
