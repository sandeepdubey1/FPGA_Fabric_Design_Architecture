# FPGA_Fabric_Design_Architecture
Documentation of FPGA Fabric Design Architecture learning, simulations and design experiments.


This repository contains all the information studied and created during the FPGA - Fabric, Design and Architecture workshop. The repository focuses on understanding FPGA architecture, FPGA design flow, open-source FPGA tools, custom FPGA fabrics, and RISC-V implementation on FPGA platforms.

Table of Contents
Introduction to FPGA
FPGA vs ASIC
## Day 1 - Exploring FPGA Basics and Vivado
FPGA Architecture
Configurable Logic Blocks
Basys3 FPGA Board
Counter Example in Vivado
Simulation and Elaboration
Synthesis
Constraints
Bitstream Generation
Timing, Power and Area Analysis
Introduction to VIO
## Day 2 - Exploring OpenFPGA, VPR and VTR
OpenFPGA
VPR Flow
VTR Flow
Timing Analysis
Post-Synthesis Simulation
Power Analysis
## Day 3 - RISC-V Core Programming Using Vivado
RTL Design
Simulation
Synthesis
Implementation
Timing Analysis
Resource Utilization
Power Analysis
## Day 4 - Introduction to SOFA FPGA Fabric
SOFA Architecture
Counter Area Analysis
Counter Timing Analysis
Post-Implementation Simulation
Power Analysis
## Day 5 - RISC-V Core on Custom SOFA Fabric
Timing Reports
Utilization Reports
Post-Implementation Simulation
References
Acknowledgements
Introduction to FPGA

FPGA (Field Programmable Gate Array) is an integrated circuit that can be configured after manufacturing. It consists of configurable logic blocks, programmable routing resources, memory elements, and I/O blocks.

FPGA vs ASIC
FPGA	ASIC
Reconfigurable	Fixed after fabrication
Faster development	Longer development cycle
Suitable for prototyping	Suitable for mass production
Higher power consumption	Lower power consumption
RTL → Bitstream	RTL → GDSII
