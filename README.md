# SevenSegmentDisplay
This is a project made using Verilog to simulate a seven segment display to display the numbers 0 to 9.

The seven_segment.v file contains the modules that represent each of the seven segments
The seven_segment_tb.v file will instantiate a new seven_segment display and display the outputs on GTKWave
The test file will create the vcd executable file seven_segment_test.vcd

To run the project, you must run the following commands in this order:
  iverilog -o test seven_segment.v seven_segment_tb.v
  vvp test
  gtkwave seven_segment_test.vcd
