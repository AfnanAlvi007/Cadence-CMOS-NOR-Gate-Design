# CMOS 2-Input NOR Gate Design Using Cadence Virtuoso

## Overview
This project presents the design and simulation of a 2-input CMOS NOR gate using Cadence Virtuoso IC617. The complete full-custom IC design flow includes schematic design, physical layout implementation, and transient simulation verification.

## Tools & Technology

- **EDA Tool:** Cadence Virtuoso IC617
- **Process Technology:** GPDK045 CMOS Technology
- **Simulation Tool:** Cadence Spectre
- **Design Method:** Full Custom IC Design

## Project Components

### 1. Schematic Design
A transistor-level schematic of a CMOS 2-input NOR gate was created using:

- PMOS pull-up network
- NMOS pull-down network
- Two input signals (A and B)
- One output node (Vout)

### 2. Physical Layout Design
The layout was implemented in Cadence Virtuoso Layout Editor, including:

- PMOS and NMOS transistor placement
- Metal interconnections
- VDD and GND power rails
- Input/output pins

### 3. Simulation Verification
Transient simulation was performed using Cadence Spectre to verify the logic functionality of the NOR gate.

The output follows the NOR truth table:

| Input A | Input B | Output Vout |
|---------|---------|-------------|
| 0       | 0       | 1           |
| 0       | 1       | 0           |
| 1       | 0       | 0           |
| 1       | 1       | 0           |


## Files Included
- Schematic file
- Layout file
- Symbol file
- Simulation files
- Design screenshots

## Author
Afnan Alvi
