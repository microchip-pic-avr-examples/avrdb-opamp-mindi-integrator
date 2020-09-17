![Microchip logo](images/microchip.png)
# Getting started with Mindi™ simulation and AVR®DB microcontrollers
This guide will get you up and running with simulating the analog OPAMP module in AVR DB family devices using the Mindi simulation tool. For a larger overview, see ["Getting Started with Analog Signal Conditioning (OPAMP)"](https://github.com/search?q=topic%3Aavr-db+topic%3Agetting-started-with-opamp+org%3Amicrochip-pic-avr-examples).
## Configuration: Integrator
The op amp can be configured to act as an integrator, using an external capacitor and resistor.
The integrator can be reset by the event system.

![Integrator](images/configuration.png)

### Mindi Simulation
![Mindi](images/mplab-mindi-analog-simulator.png)

Download and open the **Mindi schematic [here](https://github.com/microchip-pic-avr-examples/avrdb-opamp-mindi-integrator/releases/latest)**

Press the _play_ button to simulate with an example stimulus source.

### Tweaking
The rate of integration can be adjusted by changing the external component values. The internal configuration has no adjustable parameters.

### Don't have Mindi?
You can download and install the [Mindi simulation tool](https://www.microchip.com/mplab/mplab-mindi), or use another SPICE simulator of your own preference. For use with different simulators, a plain spice model can be found in "Opamp_AVR_DB.txt" to replace the mindi-optimized ".lb" 
