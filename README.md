# Low Frequency Amplifier
### Revision 1.0

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
+ *Bill of Materials*  - This contains the bill of materials in CVS, LibreOffice Calc and XML formats
+ *Drawings*  - This contains PDF and SVG outputs of schematic and PCB files
+ *Gerbers* - This contains the PCB Gerbers and drill drawings for manufacture, there is also a zip file ready to send to most manufacturers
+ *KiCad* - This contains the original KiCad schematic and PCB design files
