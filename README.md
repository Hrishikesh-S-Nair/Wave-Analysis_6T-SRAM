# 6T-SRAM Ngspice Simulation

![download](https://github.com/Hrishikesh-S-Nair/Wave-Analysis_6T-SRAM/assets/125496407/22ca6d7f-83f3-4fff-ac62-3b8ba8482736)

## Introduction

This repository contains Ngspice simulation code for a 6T-SRAM (Static Random Access Memory) cell. The 6T-SRAM cell is a fundamental building block of memory systems, commonly used in modern microprocessors and digital integrated circuits. This project aims to provide a comprehensive Ngspice simulation environment for analyzing the behavior and characteristics of a 6T-SRAM cell.

## Contents

- [Introduction](#introduction)
- [Contents](#contents)
- [6T-SRAM Cell Overview](#6t-sram-cell-overview)
- [Simulation Setup](#simulation-setup)
- [Simulation Results](#simulation-results)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## 6T-SRAM Cell Overview

The 6T-SRAM cell is a type of static memory cell that consists of six transistors. It is widely used due to its stability, non-volatility, and ability to retain data as long as power is supplied. The cell includes two cross-coupled inverters and two access transistors for read and write operations. Understanding the behavior of the 6T-SRAM cell is crucial for memory design and optimization.

## Simulation Setup

The simulation setup involves creating a detailed SPICE netlist for the 6T-SRAM cell, defining transistor models, and specifying input signals for read and write operations. The parameters of the transistors, such as width, length, and threshold voltage, play a significant role in the cell's performance.

## Simulation Results

The Ngspice simulation provides various results and characteristics of the 6T-SRAM cell, including:

- Read and write stability
- Read and write access times
- Read and write noise margins
- Power consumption during read and write operations
- Data retention time

## Getting Started

To run the Ngspice simulations, follow these steps:

1. Clone this repository to your local machine.
2. Install Ngspice (if not already installed).
3. Navigate to the project directory.
4. Open the Ngspice netlist file for the 6T-SRAM cell.
5. Run the simulation using Ngspice commands.

## Usage

You can use this repository to:

- Understand the behavior of a 6T-SRAM cell through Ngspice simulations.
- Modify the parameters of the transistors and analyze their impact on cell performance.
- Extend the simulations to include larger memory arrays and more complex memory systems.
- Compare different SRAM cell designs and their trade-offs.

## Contributing

Contributions to this repository are welcome! If you find any issues, want to enhance the simulations, or have new insights to share, please feel free to open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](insert_license_url_here).

