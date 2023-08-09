# Theory:

To design a Synchronous finite state machine, following steps are followed.
1. Word Statement of The Problem
2. Design State Diagram
3. Design State Table
4. Reduced Standard Form State Table
5. Develop State Assignment, Transition and Output Table
6. Choose Flip-Flop type, form the excitation table
7. Solve k-maps and develop minimal expressions.
8. Implement the expressions.

Here are the steps to build a binary adder using the above steps. [Ref. https://www.slideshare.net/adarshpatel2/synchronous-state-machine-design](https://www.slideshare.net/adarshpatel2/synchronous-state-machine-design)

1. State Diagram & State Table
    
<center>
<img src="./images/E10p1.png" style="width:50%">

</center>

2. Reduced Standard Form State Table
<center>
<img src="./images/E10p2.png" style="width:50%">

</center>


3. Excitation table with D FlipFlop & Expression reduction using k-maps.

<center>
<img src="./images/E10p3.png" style="width:50%">

</center>


4. Implementation
<center>
<img src="./images/E10p4.png" style="width:50%">

</center>


## Simulation of the above circuit

In the circuit:

Input Bits: 101 and 102 

Output Bit: 106

Next State Bit: 103

## Below are the transition and output for Present State: 0 (A)
<center>
<img src="./images/E10p5.png" style="width:50%">

### Present State: 0, Input 00, Next State: 0, Output: 0
</center>



<center>
<img src="./images/E10p6.png" style="width:50%">

### Present State: 0, Input 01, Next State: 0, Output: 1
</center>




<center>
<img src="./images/E10p7.png" style="width:50%">

### Present State: 0, Input 10, Next State: 0, Output: 1
</center>


<center>
<img src="./images/E10p8.png" style="width:50%">

### Present State: 0, Input 11, Next State: 1, Output: 0
</center>



## Below are the transition and output for Present State: 1 (A)

<center>
<img src="./images/E10p9.png" style="width:50%">

### Present State: 1, Input 01, Next State: 1, Output: 0
</center>


<center>
<img src="./images/E10p10.png" style="width:50%">

### Present State: 1, Input 10, Next State: 1, Output: 0
</center>


<center>
<img src="./images/E10p11.png" style="width:50%">

### Present State: 1, Input 11, Next State: 1, Output: 1
</center>



<center>
<img src="./images/E10p12.png" style="width:50%">

### Present State: 1, Input 00, Next State: 0, Output: 1
</center>


