# LC3101-Assembler
This program is a cycle-accurate behavioral simulator for a pipelined implementation of the LC3101, complete with data forwarding and
simple branch prediction. It reads assembly code from an input file, parses each line to check for valid labels, instructions, and arguments, and translates the instructions into machine code, replacing symbolic labels with their corresponding addresses. The resulting machine code is outputted to a specified file, allowing the assembly code to be run by a compatible virtual machine or simulator.
