# DECODER2TO4

**AIM:**

To simulate and synthesis decoder using vivado.

**APPARATUS REQUIRED:**

vivado 2023.2 software.

**PROCEDURE:**

STEP:1 Start the vivado software, Select and Name the New project.

STEP:2 Select the device family, device, package and speed.

STEP:3 Select new source in the New Project and select Verilog Module as the Source type.

STEP:4 Type the File Name and module name and Click Next and then finish button. Type the code and save it.

STEP:5 Select the run simulation and then run Behavioral Simulation in the Source Window and click the check syntax.

STEP:6 Click the simulation to simulate the program and give the inputs and verify the outputs as per the truth table.

STEP:7 compare the output with truth table.

**Truth Table and Circuit Diagram\******

![301806071-e565d523-f8b2-4e01-8888-0eed4d07ec24](https://github.com/pullurur/DECODER2TO4/assets/161436550/fbfb246c-a0cc-4c90-b969-8d5d780a758b)


**VERILOG CODE:**

module decoder(a,b,d);

input a,b;

output [3:0]d;

and g1(d[0],~a,~b);

and g2(d[1],~a,b);

and g3(d[2],a,~b);

and g4(d[3],a,b);

endmodule

**OUTPUT:**

![318266578-07abc1ad-d8da-427c-afbf-3d05ab65dba1](https://github.com/pullurur/DECODER2TO4/assets/161436550/193bb05d-7c5c-480b-8224-8eb5a71d7a17)

**RESULT:**

Thus the verilog program for decoder has been simulated and verified successfully.

