# Low Frequency Amplifier
### Revision 1.0
<img src="./Schematics/Electrical diagram - Transfer PCB.jpg" width='650'>

---
# README

### What is this repository?

**Quick summary**

This is a BJT based Class AB low frquency amplifier (audio amplifier) PCB design using SMD technology.

This repository contains the OrCad design files, manufacturing Gerber/drill files, PDF/drawing files, and relevant documenation for this board.

### Design characteristics

+ Input signal, *ui* in the range: ±1 [V]
+ Output load, *RL*: 40 [Ω]
+ Input resistance *Ri* > 0.1 [MΩ]
+ Output resistance *Ro* < 0.8 [Ω]
+ Voltage gain, *Av*: 10
+ Operating temperature range: -20 - 120°C
+ The presence of supply voltages is signaled by an LED

### Project folder structure

Starting from the top level:
+ *Bill_of_Materials*  - This contains the bill of materials in .xls and .BOM formats
+ *Data sheets* - This contains the data sheets for the electronic devices used
+ *Layout* - This contains the PCB Gerbers and drill file for manufacture, there is also a .jpg image with the PCB layout
+ *Project docs* - This contains the relevant documenation for this project (in Romanian)
+ *Schematics* - This contains the original OrCad schematic and design files. There are two folders inside: 
    - *Simulation* - contains the OrCad schematic used for circuit simulation
    - *Transfer PCB* - contains the OrCad schematic used for exporting the circuit to the OrCad PCB Editor
+ *Simulations* - This folder contains images of different simulations that prove the circuit is working adequately
