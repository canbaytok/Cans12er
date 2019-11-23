# Cans12er
![Cans12er](https://i.imgur.com/ZsO6QSI.jpg)

A 12-key, orthogonal keypad designed by me!

Hardware Supported: Pro Micro Atmega32u4

# Build Instructions

## Parts

- 1 x 3D printed bottom case part
- 1 x 3D printed top case part
- 12 x CherryMX switches
- 12 x diodes (SOD-123 package)
- 6 x 0 Ω 0805 bridges
- 1 x Arduino Pro Micro ATmega32u4 MCU
- 1 x home-routed or ordered PCB
- 4 x 8mm long and ø3mm countersink screw
- 1 x MicroUSB cable
- 7 x copper wire (each ~10cm long)
- a little hot glue
- 1 x DIP4 switch (optional)

## Tools

- Screwdriver
- Soldering Station
- Wire Cutter
- 3D Printer
- CNC Router

## Instructions

- solder the diodes and resistor bridges to the PCB
- insert the 12 CherryMX switches into the 3D printed top part
- insert the top part assembly into the pcb and solder the 24 pins to the PCB
- strip the isolation of the copper wires and solder one end of each wire to the pcb
- solder the row wires to the pins A0, D15, D14 of the Pro Micro
- solder the column wires to the pins D3, D4, D5, D6 of the Pri Micro
- hot glue the Pro Micro into the 3D printed bottom part so that the MicroUSB port and the cutout in the bottom part align
- you can optionally hot glue a DIP4 switch next to the GND and RST pins of the Pro Micro and solder two pins of the DIP4 switch to them (to reprogramm the MCU)
- close the 3D printed bottom part with the top part and screw the 4 screws in

Schematic can be found here: [EasyEDA](https://easyeda.com/senordoenermann/mediapad)