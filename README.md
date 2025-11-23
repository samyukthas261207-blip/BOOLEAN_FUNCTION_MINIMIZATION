# BOOLEAN_FUNCTION_MINIMIZATION

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

module upcounter(clk,rst,count);
input clk,rst;
output reg[3:0]count;
always@(posedge clk or negedge rst)
begin
if(!rst)
count <= 4'b0000;
else
count <= count+1;
end
endmodule

Developed by:samyuktha s
RegisterNumber:25017544


**Output:**
<img width="1920" height="1080" alt="Screenshot (132)" src="https://github.com/user-attachments/assets/4c9cac0e-a4be-483a-93cd-3edb4f02fcbb" />

**Timing Diagram**
<img width="1920" height="1080" alt="Screenshot (131)" src="https://github.com/user-attachments/assets/ac371a61-c7b1-43e7-bac6-1d0b32b08147" />


**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

