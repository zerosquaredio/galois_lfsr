# galois_lfsr
# Charley Lucas
# zerosquared.io


SystemVerilog Galois LFSR Implementation and UVM Testbench

Simulation at EDA Playground:  https://www.edaplayground.com/x/5VmJ

-----------------------------
Project Documentation
-----------------------------
doc/Reference.txt                             - References and whitepapers regarding RTL and validation technical issues.
doc/spec/Galois_LFSR_Shift_Register_v0.1.docs - Specification (in progress)
doc/spec/Galois_LFSR_Calculations.xlsx        - Spreadsheet of calculations for different bits-per-clock values
doc/spec/Galois_LFSR.vsdx                     - LFSR-Related Visio Diagrams
doc/UVM_Testbench.vsdx                        - Testbench-related Visio Diagrams

-----------------------------
Tools
-----------------------------
tools/glfsr:  C++ implementation of LFSR for clock-by-clock register value comparisons
tools/generate_glfsr:  Python script to generate verilog for an LFSR of custom width and polynomial at a fixed bits-per-clock value (in progress)
