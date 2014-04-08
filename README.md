CE_4
====

So yeah, this is a readme

My process for designing the assembly language code for this CE was to first read the 
PRISM manual to get more familiar with the device and instructions. Afterwards, I went
about going through each scenario and starting my design.

For the first program, memory manipulation, the process was pretty straight forward. I used the memory assignment commands to assign values to the assigned addresses

For math, I loaded a value from the register, added it to itself to double it, and then i added $C which served to subtract 4 from the value, afterwards I output the result on port 2 and kept looping from there

For the loop, I took the input of Port 3, output it on Port 0, added $F which served to subtract 1, output the result on Port 1, decremented 1 again, output on Port 2, added 1, and kept the loop running over and over again starting from OUT 0.
