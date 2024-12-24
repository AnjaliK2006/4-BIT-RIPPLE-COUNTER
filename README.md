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

/* write all the steps invloved */

**PROGRAM**

/* Program for 4 Bit Ripple Counter and verify its truth table in quartus using Verilog programming.

 Developed by: Anjali K
 RegisterNumber: 24900073

 ![Screenshot 2024-12-24 154539](https://github.com/user-attachments/assets/375191d9-335d-4374-adeb-016bb4133398)

*/

**RTL LOGIC FOR 4 Bit Ripple Counter**
![Screenshot 2024-12-24 154513](https://github.com/user-attachments/assets/2f7fcd58-5691-42fe-97a7-2a3e8664a7b1)

**TIMING DIGRAMS FOR 4 Bit Ripple Counter**
![Screenshot 2024-12-24 154737](https://github.com/user-attachments/assets/a8d1e7b0-cf93-49bb-8485-662e820df2c4)

**RESULTS**
 The 4-bit ripple counter was successfully implemented using Verilog in Quartus Prime. The functionality was verified using a testbench, which simulated the counter's operation. The counter correctly counted from 0000 to 1111, incrementing by 1 on each clock pulse. After reaching 1111, the counter reset to 0000, as expected. The timing diagrams and the functional table showed that the ripple counter operated as intended, with each flip-flop toggling on the rising edge of the previous flip-flop's output. The simulation results confirmed the correct operation of the 4-bit ripple counter.
