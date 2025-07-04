COMPANY: CODTECH IT SOLUTIONS

NAME: GOVINDA MAHARANA

INTERN ID: CT04DF2309

DOMAIN: VLSI

DURATION: 4 WEEEKS

MENTOR: NEELA SANTOSH

#DESCRIPTION OF TASK 3 

Design a 4-Stage Pipelined Processor with Basic Instructions like ADD, SUB, and LOAD
This task challenged me to design a 4-stage pipelined processor, capable of executing basic instructions such as ADD, SUB, and LOAD. Pipelining is a fundamental concept in processor design that allows multiple instructions to be processed simultaneously at different stages, thereby improving overall throughput.

The processor was divided into 4 stages:

IF (Instruction Fetch)

ID (Instruction Decode)

EX (Execute)

WB (Write Back)

Each stage was implemented as a separate Verilog module to maintain modularity. I used Visual Studio Code as the editor, and simulations were done using ModelSim. The design had components such as a program counter (PC), instruction memory, register file, and ALU. The control logic ensured that instructions moved through the pipeline correctly without conflicts.

A major part of the task was handling data dependencies and ensuring proper forwarding or stalling if needed. Although this was a basic version without full hazard control, it gave an insight into how real processors like MIPS or RISC-V handle instruction execution.

The testbench was written to provide a sequence of instructions, and I analyzed how each instruction passed through the stages over multiple clock cycles using waveform simulation. For example:

At time 10 ns, the ADD instruction enters the IF stage.

At time 20 ns, it moves to the ID stage, while the next instruction begins IF.

This task has high applicability in real-world CPU design. Pipelining is used in nearly every modern processor to boost performance. Whether it's a simple ARM Cortex processor or a high-end Intel Core i9, pipelining is the core design principle.

Completing this task taught me about instruction-level parallelism, control unit design, and timing management in processors. It was like building a small-scale version of a RISC architecture, which is very useful for careers in embedded systems, digital design, and chip architecture.

#OUTPUT

