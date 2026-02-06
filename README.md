# arduinoLEDcontrolunit

Hardware documentation and assembly guide for building an Arduino-based LED control unit for fluorescence microscopy applications.

## Overview

This repository provides comprehensive documentation for constructing the hardware interface between Arduino controllers and LED illumination systems used in FRET microscopy and other fluorescence imaging applications.

## Contents

- `Layout Arduino.png` - Arduino board layout and pin configuration diagram
- `Anschluss LED PowerSupply.png` - LED power supply connection schematic
- `arduinoLEDcontrolunit Info.pdf` - Complete assembly and wiring documentation

## Documentation

The PDF manual (`arduinoLEDcontrolunit Info.pdf`) contains detailed information about:
- Component specifications
- Wiring diagrams
- Pin assignments
- LED driver connections
- Power supply configuration
- Safety considerations

## Hardware Components

The control unit typically includes:
- Arduino microcontroller board
- LED driver circuits
- Power supply connections
- Current limiting resistors
- Connectors for multiple LED channels
- Protection circuitry

## Assembly Guide

1. Review the complete documentation in `arduinoLEDcontrolunit Info.pdf`
2. Gather all required components
3. Follow the wiring diagram in `Layout Arduino.png`
4. Connect LEDs and power supply as shown in `Anschluss LED PowerSupply.png`
5. Test each channel individually before full operation
6. Upload firmware from [Arduino-for-LEDControl-](https://github.com/christianhermann/Arduino-for-LEDControl-)

## Safety Warning

⚠️ **Important:** High-power LEDs and their drivers can generate significant heat and current. Ensure proper:
- Thermal management
- Current limiting
- Electrical isolation
- Ventilation

## Related Projects

This hardware works with:
- [Arduino-for-LEDControl-](https://github.com/christianhermann/Arduino-for-LEDControl-) - Arduino firmware
- [EnhancedLEDControl](https://github.com/christianhermann/EnhancedLEDControl) - MATLAB control software
- [FRETControl](https://github.com/christianhermann/FRETControl) - Alternative control interface

## Support

For hardware-specific questions, refer to the included PDF documentation. For firmware issues, see the Arduino firmware repository.
