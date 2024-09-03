Name: Naini Rakesh

Company: CODTECH IT SOLUTIONS

ID: CT6WDS1647

Domain: VLSI

Duration: AUGUST to SEPTEMBER 2024

Mentor: NEELA SANTHOSH KUMAR

OVERVIEW OF THE PROJECT

Project : FLOATING POINT UNIT (FPU) DESIGN

![image](https://github.com/user-attachments/assets/5c2b7e59-8d22-42a4-8361-fa8b5a196f90)

![image](https://github.com/user-attachments/assets/4a861ca6-4d62-4e6e-babc-c1e9f77d8962)

![image](https://github.com/user-attachments/assets/5ec54346-0b1c-4c32-89a2-60c9a84abfff)


![image](https://github.com/user-attachments/assets/63465c6b-f122-4db7-a3a3-14b5756facd4)



Software:

Verilog: A hardware description language (HDL) used for designing and testing digital circuits.

Testbench: A Verilog module that provides input stimuli and checks output responses for a device under test (DUT).

Key Points:

Module Declaration:

FloatAdditionTB: Testbench module name.

XLEN = 32: Parameter defining the bit width of floating-point numbers.

Registers and Wires:

A and B: Input registers for floating-point numbers.

clk: Clock signal register.

overflow, underflow, exception: Registers for flags.

result: Output wire for the result.

Floating-Point Addition Instance:

FloatingAddition F_Add: Instantiates the floating-point addition module.

Test Vectors:

Five test cases with different input values.

Expected Value Calculation:

Computes the expected result using the formula: (2^(exponent-127)) * (mantissa/2^23) * (-1)^sign.

Display Results:

$display prints the expected value and result for each test case.

Simulation Control:

#20 waits for 20 time units between test cases.

$finish ends the simulation.

Key aspects:

Verilog testbench for floating-point addition

Five test cases with varying input values

Expected value calculation using the IEEE 754 floating-point representation formula

Displaying results for comparison

Simulation control using Verilog timing constructs

This testbench verifies the functionality of the floating-point addition module by providing various input scenarios and checking the output results.
