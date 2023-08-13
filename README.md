# Wave-Analysis_6T-SRAM
The provided code represents a digital circuit implementation written in the SPICE netlist format. It consists of a precharge circuit, a sense amplifier circuit, and control statements for simulation.

The circuit implements a basic SRAM (Static Random Access Memory) cell using CMOS (Complementary Metal-Oxide-Semiconductor) technology. SRAM is a type of volatile memory commonly used in computer systems for fast data storage.

The precharge circuit, defined in the "precharge" subcircuit, consists of two p-channel MOS transistors (m1 and m2) connected to a power supply (vcc) and a bitline (bl). This circuit is responsible for precharging the bitline to a logical high voltage (vcc) before reading or writing data.

The sense amplifier circuit, defined in the "senseamp" subcircuit, amplifies the voltage difference between the bitline (bl) and its complement (blbar) to improve the stability and accuracy of the read operation. It includes a series of CMOS transistors (m1 to m9) connected in a specific configuration.

The control statements section sets up the simulation parameters and instructs the simulator to perform a transient analysis of the circuit. It then plots the waveforms of various circuit nodes, including the bitline (bl), its complement (blbar), the data node (q), its complement (qbar), and the wordline (wl).

In summary, this code implements a simple SRAM cell and simulates its behavior to analyze the waveforms of critical signals during read and write operations. It can be used to evaluate the performance and functionality of the SRAM circuitry

![Conventional-6T-SRAM-Cell-7](https://github.com/Hrishikesh-S-Nair/Wave-Analysis_6T-SRAM/assets/125496407/a87ab13e-cc78-43fc-87b0-750dc05f35e6)

