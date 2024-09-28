# Full_Adder_nclaunch-sim

## Aim:
To write a verilog code for 4bit adder and verify the functionality using Test bench.

# Tool Required: 
Functional Simulation: nclaunch Simulator (nclaunch) 

# 4-bit Adder Design:
To construct a 4-bit adder, need to chain together four 1-bit full adders. Each full adder computes the sum and carry for one bit of the two numbers. The carry-out from one adder feeds into the carry-in of the next adder in the sequence. This process adds the two 4-bit numbers bit by bit, with the carry propagating through each stage, resulting in a final sum and carry-out at the end.
To design a 1-bit full adder, the first step is to create a truth table that represents all possible combinations of the inputs (A, B, and CIN) and the corresponding outputs (Sum(S) and COUT).

![image](https://github.com/user-attachments/assets/716a26b6-a449-42e0-9e2d-cdbaa4b291b9)

Here’s the truth table for a 1-bit full adder:

![tt](https://github.com/user-attachments/assets/0b3ab24f-1d7e-4a01-80ce-5e7406f4082b)

Fig 1 : Diagram and truth table of full adder

# Logic Expressions:
1.	Sum (S):
S=A⊕B⊕CIN
Where ⊕ represents XOR.
2.	Carry out (COUT):
COUT=(A&B) | (CIN&(A^B))

![image](https://github.com/user-attachments/assets/7d6fa554-2614-4f19-aa68-65c9e6153caa)

Fig:2 Diagram of 4 Bit Adder






