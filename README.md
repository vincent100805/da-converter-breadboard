# D/A Converter — Breadboard Implementation

**Overview**  
Digital-to-Analog Converter (DAC) implemented on a breadboard using a divide-by-16 counter (74LS74 D flip-flops), an R-2R resistor ladder, and a 741 op-amp as a summing/buffering amplifier.

**Components**
- 2 × 74LS74 D flip-flops (used to form the divide-by-16 counter)
- 1 × 741 op-amp
- R-2R resistor ladder 
- Breadboard, jumper wires, power supply 
- Oscilloscope and function generator

**What I did**
- Assembled the divide-by-16 counter and R-2R ladder on a breadboard.
- Measured output analog waveform and verified linear steps corresponding to the binary inputs.
- Used an oscilloscope to capture voltage levels and time-domain response.
- Confirmed timing using clock input from a function generator.

**Results**
- Successfully produced discrete analog voltage steps corresponding to binary counts (0–15).
