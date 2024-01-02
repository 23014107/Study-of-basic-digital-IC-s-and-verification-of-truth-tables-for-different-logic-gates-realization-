# NAME: RAMYA.P
# REFERANCE NUMBER: 212223240137
# EXPERIMENT 1: Study-of-basic-digital-IC-s-and-verification-of-truth-tables-for-different-logic-gates-realization-
 AIM:
To study about the different digital IC’s and to verify the truth table in Quartus for the basic logic gates using Verilog programming.

Equipments Required:
Hardware – PCs, Cyclone II , USB flasher
Software – Quartus prime
Theory
Introduction
Logic gates are the basic building blocks of any digital system. Logic gates are electronic circuits having one or more than one input and only one output. The relationship between the input and the output is based on a certain logic. Based on this, logic gates are named as

AND gate
OR gate
NOT gate
NAND gate
NOR gate
Ex-OR gate
Ex-NOR gate
1) AND gate
The AND gate is an electronic circuit that gives a high output (1) only if all its inputs are high. A dot (.) is used to show the AND operation i.e. A.B or can be written as AB
Y= A.B

2) OR gate
The OR gate is an electronic circuit that gives a high output (1) if one or more of its inputs are high. A plus (+) is used to show the OR operation.

Y= A+B

3) NOT gate
The NOT gate is an electronic circuit that produces an inverted version of the input at its output. It is also known as an inverter. If the input variable is A, the inverted output is known as NOT A. This is also shown as A' or A with a bar over the top, as shown at the outputs.

Y= A'

4) NAND gate
This is a NOT-AND gate which is equal to an AND gate followed by a NOT gate. The outputs of all NAND gates are high if any of the inputs are low. The symbol is an AND gate with a small circle on the output. The small circle represents inversion.

Y= (AB)’

5) NOR gate
This is a NOT-OR gate which is equal to an OR gate followed by a NOT gate. The outputs of all NOR gates are low if any of the inputs are high. The symbol is an OR gate with a small circle on the output. The small circle represents inversion.

Y= (A+B)’

6) Ex-OR gate
The 'Exclusive-OR' gate is a circuit which will give a high output if either, but not both of its two inputs are high. An encircled plus sign (⊕) is used to show the Ex-OR operation.

Y= A⊕B

7) Ex-NOR gate
The 'Exclusive-NOR' gate circuit does the opposite to the EX-OR gate. It will give a low output if either, but not both of its two inputs are high. The symbol is an EX-OR gate with a small circle on the output. The small circle represents inversion.

Y= A⊕B

Procedure
Connect the supply (+5V) to the circuit
Switch ON the main switch
Press the switches for inputs “A” and “B”. The switch is ON state when 1 is pressed. The switch is OFF state when 0 is pressed.
If the output is 1, then the bulb glows.
Check all the gates following the same procedure.
# Program:
                               module logicgates(a,b,y1,y2,y3,y4,y5,y6,y7);
                               input a,b;
                               output y1,y2,y3,y4,y5,y6,y7;
                               and (y1,a,b);
                               or (y2,a,b);
                               not (y3,a);
                               xor (y4,a,b);
                               nand (y5,a,b);
                               nor(y6,a,b);
                               xnor (y7,a,b);
                               endmodule

#RTL REALIZATION:
![285830260-f7726398-f2fd-47c7-9791-e79e0afa82f6](https://github.com/23014107/Study-of-basic-digital-IC-s-and-verification-of-truth-tables-for-different-logic-gates-realization-/assets/151625620/ec8bb577-8ac0-4629-ae4d-89197e78be73)

# TRUTH TABLE:


![285830630-96f13d5f-ec9c-48d5-ba7a-f5da41cbf160](https://github.com/23014107/Study-of-basic-digital-IC-s-and-verification-of-truth-tables-for-different-logic-gates-realization-/assets/151625620/013269e0-8db4-44b1-8366-6b710efd5a8a)


# TIMING DIAGRAM:


![285832412-0422062a-f7db-44ec-b9e4-94a5bb53755b](https://github.com/23014107/Study-of-basic-digital-IC-s-and-verification-of-truth-tables-for-different-logic-gates-realization-/assets/151625620/77a0bcd9-f427-4711-873f-c6c15b526034)



# Result:
Thus the different digital IC’s are studied and the truth table for different logic gates are verified.
