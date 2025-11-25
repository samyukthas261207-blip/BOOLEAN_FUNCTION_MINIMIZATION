**AIM:**

To implement the given logic function verify its operation in Quartus using Verilog programming.

F1= A’B’C’D’+AC’D’+B’CD’+A’BCD+BC’D 

F2=xy’z+x’y’z+w’xy+wx’y+wxy

**Equipment Required:**

Hardware – PCs, Cyclone II , USB flasher

**Software – Quartus prime**

**Theory**

**Logic Diagram**

**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**
1st program

module funct1(a,b,c,d,f1);
input a,b,c,d;
output f1;
assign f1=((~b & ~d)|(~a & b & d)|(a & b & ~c));
endmodule

2nd program

module funct2(w,x,y,z,f2);
input w,x,y,z;
output f2;
assign f2=((~y & z)|( w & y )|(x & y));
endmodule


Developed by:samyuktha s
RegisterNumber:25017544



**Output:**
1st program  output

<img width="1920" height="1080" alt="Screenshot (134)" src="https://github.com/user-attachments/assets/9daa679f-5a31-4267-86ca-90bf95a09f5a" />

2nd program output

<img width="1920" height="1080" alt="Screenshot (136)" src="https://github.com/user-attachments/assets/49b2c81d-69b6-4640-88db-e1de490fbcc5" />


**Timing Diagram**
1st program diagram

<img width="1920" height="1080" alt="Screenshot (135)" src="https://github.com/user-attachments/assets/83d5cd41-0e18-4b59-a1e6-bb1148eaded6" />

2nd program diagram

<img width="1920" height="1080" alt="Screenshot (137)" src="https://github.com/user-attachments/assets/4e4c72ba-0ce6-4e80-8d8a-35c4916e4731" />


**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

