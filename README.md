# BOOLEAN_FUNCTION_MINIMIZATION

**AIM:**

To implement the given logic function verify its operation in Quartus using Verilog programming.

F1= A’B’C’D’+AC’D’+B’CD’+A’BCD+BC’D 

F2=xy’z+x’y’z+w’xy+wx’y+wxy

**Equipment Required:**

Hardware – PCs, Cyclone II , USB flasher

**Software – Quartus prime**

**Theory**

![image](https://github.com/user-attachments/assets/50a74105-f6d9-4ccf-94e9-b2b1ac56999b)



**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**
```
module exp2(a,b,c,d,f1,w,x,y,z,f2);
input a,b,c,d,w,x,y,z;
output f1,f2;
assign f1=((~b&~c)|(~a&b&d)|(a&b&~c));
assign f2=((~y&z)|(x&y)|(w&y));
endmodule

```
 

Developed by:Sribalaji RegisterNumber:24900249


**RTL realization**

![Screenshot 2024-12-10 134124](https://github.com/user-attachments/assets/9810cdfe-04f1-4156-b022-deca9bb2fe0c)


**Timing Diagram**

![Screenshot 2024-12-10 134407](https://github.com/user-attachments/assets/986db749-d39a-4ed4-83cc-773675b27aa7)


**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

