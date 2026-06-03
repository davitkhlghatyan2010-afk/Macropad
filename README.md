# Micropad

A compact macro-pad project built with the Seeed Studio XIAO. This project combines a custom PCB design with flexible firmware written in Python.

## Hardware
- **Controller:** Seeed Studio XIAO [Insert Model: e.g., RP2040, ESP32-C3]
- **Design:** Custom PCB designed to be compact and efficient for macro inputs.
- **Production:** Gerber files are available in the `/hardware` folder.

## Firmware
- **Language:** Python (CircuitPython)
- **Features:** USB HID (Human Interface Device) support for customizable key macros.

## Project Status
- [ ] Hardware assembly
- [ ] Firmware development
- [ ] Testing and finalization

## Customization
The Micropad is highly customizable. Users can modify key combinations by editing the `config.json` file located on the device. Simply update the key-action mapping, save the file, and the device will apply the changes instantly.

## Usage
