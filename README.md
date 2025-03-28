# Ex No: 04 - Design & Implementation of 6T SRAM Cell Using Cadence EDA Tools

## Aim
The aim is to design and implement a 6T SRAM (Static Random-Access Memory) cell using Cadence EDA tools and verify its functionality through transient analysis simulation.

## Tools Required

### Cadence EDA Suite
- **Virtuoso Schematic Editor** (for circuit design)
- **Spectre Simulator** (for circuit simulation)

### Process Design Kit (PDK)
- CMOS technology library (45nm node)  

### Computer System
- Minimum **4GB RAM** and a **multi-core processor**

## Procedure:
### 1. Launch Cadence Virtuoso Environment:
   - Open the Cadence Virtuoso tool and set up the working library.
   - Create a new schematic cell view for the 6T SRAM cell design.

### 2. Schematic Design:
   - Select NMOS and PMOS transistors from the library.
   - Construct the 6T SRAM cell with two cross-coupled inverters and access transistors.
   - Connect the wordline (WL), bitlines (BL, BLB), and power supply connections.

### 3. Simulation:
   - Check the design for errors and proceed with simulation.
   - Launch the Analog Design Environment (ADE).
   - Perform transient analysis to verify read and write operations.
   - Set up input stimulus and analyze the output waveform.

## Schematic Diagram
![Screenshot 2025-03-28 140743](https://github.com/user-attachments/assets/e6cda0a1-87b7-4976-8135-a5f3275aa0cf)

#### 1. Schematic of 6T SRAM Cell:

![Screenshot 2025-03-28 140858](https://github.com/user-attachments/assets/485a0179-70aa-428a-8f97-12edab84b6c4)

![Screenshot 2025-03-28 140834](https://github.com/user-attachments/assets/6a5a9cfb-7f59-4c5f-8ccc-1e6a1779c4f6)



## Output
#### 1. Transient Analysis Output:
![Screenshot 2025-03-28 140700](https://github.com/user-attachments/assets/de7b050a-48d5-4848-9b6a-2f071c448ff7)

## Results:
1. Successfully designed the 6T SRAM cell schematic using Cadence EDA tools.
2. Performed transient analysis, verifying the read and write operations of the SRAM cell.
3. Observed correct switching behavior in response to control signals.


