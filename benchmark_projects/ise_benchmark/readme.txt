
Xilinx ISE benchmark project
=========================


Konstantin Pavlov, pavlovconst@gmail.com


This project uses adapted verilog version of dynamic_delay.sv module to model
both high-register count and combinational-intensive design.

To see total time spent for the compilation please use some sort of external
timer. This will give you some quantitive charachteristic of
your environment processing power.

You can also compare how different machines and environments deal with this
typical design when compiling for FPGAs. I use only pure RTL code here with
intention to leave an opportunity to compare compilation time across all
possible IDE`s and even across all FPGA vendors.

"quartus_benchmark" is a similar project for Altera / Intel devices
"vivado_benchmark" is a similar project for newer Xilinx / AMD devices
"gowin_benchmark" is a similar project for chinese Gowin devices

