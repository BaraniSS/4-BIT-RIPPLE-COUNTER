# 4-BIT-RIPPLE-COUNTER

**AIM:**

To implement  4 Bit Ripple Counter using verilog and validating their functionality using their functional tables

**SOFTWARE REQUIRED:**

Quartus prime

**THEORY**

**4 Bit Ripple Counter**

A binary ripple counter consists of a series connection of complementing flip-flops (T or JK type), with the output of each flip-flop connected to the Clock Pulse input of the next higher-order flip-flop. The flip-flop holding the least significant bit receives the incoming count pulses. The diagram of a 4-bit binary ripple counter is shown in Fig. below.

![image](https://github.com/naavaneetha/4-BIT-RIPPLE-COUNTER/assets/154305477/cb4b74d4-31ab-4359-95d0-d22e67daba13)

In timing diagram Q0 is changing as soon as the negative edge of clock pulse is encountered, Q1 is changing when negative edge of Q0 is encountered(because Q0 is like clock pulse for second flip flop) and so on.

![image](https://github.com/naavaneetha/4-BIT-RIPPLE-COUNTER/assets/154305477/a573a7d6-014e-4e54-93e6-e2ac9530960b)

![image](https://github.com/naavaneetha/4-BIT-RIPPLE-COUNTER/assets/154305477/85e1958a-2fc1-49bb-9a9f-d58ccbf3663c)

**Procedure**

/* 1.Write the Verilog code in Quartus Prime for the 4-bit ripple counter.


2.Compile and run the program to ensure it is error-free


3.Generate the RTL schematic to visualize the flip-flop connections.


4.Create nodes for the clock input (CLK) and counter outputs (Q0, Q1, Q2, Q3).


5.Simulate the design for multiple clock cycles to observe the ripple effect.


6.Verify the timing diagrams to ensure the counter toggles through all states (0000 to
1111).


7.Save the RTL schematic and timing diagrams for documentation and validation. */

**PROGRAM**

/* Program for 4 Bit Ripple Counter and verify its truth table in quartus using Verilog programming.

 Developed byBARANI S S    RegisterNumber:24900119

 ![Screenshot 2024-12-10 104338](https://github.com/user-attachments/assets/cb806b12-a44d-4d59-909d-128a68b286b6)
 ![Screenshot 2024-12-10 104348](https://github.com/user-attachments/assets/0d05441f-cc43-4ece-9ec0-b3998623ac9f)




**RTL LOGIC FOR 4 Bit Ripple Counter**

![Screenshot 2024-12-10 104356](https://github.com/user-attachments/assets/21f41c53-0e9c-40e7-a3fa-b4c25ae66b21)




**TIMING DIGRAMS FOR 4 Bit Ripple Counter**

![Screenshot 2024-12-10 104404](https://github.com/user-attachments/assets/21cf35ac-0f7e-4e4b-b922-6d573814965a)

TRUTH TABLE:

![Screenshot 2024-12-10 104413](https://github.com/user-attachments/assets/f800d030-c543-411d-8f57-2a605b660656)




**RESULTS**

Thus, the 4-bit Ripple Counter was successfully implemented, and its functionality was
validated using the truth table.
