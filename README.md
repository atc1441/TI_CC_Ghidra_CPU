# Texas Instruments CCxxxx Ghidra CPU Plugin
Ghidra Plugin for Texas Instrument CC 8051 core SOC's especially CC1110 and CC2510

This helps to name the default SFR for the standard Peripheral as well as Radio, USB and I2S Register

Example SOC: 
https://www.ti.com/product/CC2510
https://www.ti.com/product/CC1110-CC1111

## Install:
  Simply copy the "8051CC" folder to <Ghidra>/Ghidra/Processors/
  
  On the next file opening select "8051CC" as "Language"

  
## Compile with changes use:
  <Ghidra>/support/sleigh.bat -a <Ghidra>/Ghidra/Processors/8051CC
