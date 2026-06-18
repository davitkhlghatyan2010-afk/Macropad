# Custom 6-Key Macropad with Rotary Encoder & OLED Display

A compact, DIY custom macropad built around the **Seeed Studio XIAO RP2040** microcontroller and running the open-source **KMK Firmware** (CircuitPython). This pad features 6 mechanical keyswitches, a 7-pixel chained NeoPixel RGB strip, a volume rotary encoder, and an SSD1306 128x64 OLED display running custom frame animations.

## 🚀 Features
* **Dynamic JSON Configuration:** Keybinds are completely modular and loaded on-the-fly from a local `commands.json` file without modifying the main firmware.
* **Volume Rotary Encoder:** Clockwise/counterclockwise scroll tracking mapped to system volume adjustments.
* **Custom OLED Animations:** Bypasses default KMK layer readouts to loop custom 1-bit `.pbm` flipbook animations.
* **RGB Breathing Effect:** Smooth breathing lighting profile across a 7-pixel NeoPixel LED chain.

---

## 📂 File Structure Explained

Your `CIRCUITPY` drive root should look like this:

```text
├── kmk/                  # KMK Firmware Library Folder
├── boot.py               # Hardware/USB-level configuration script
├── main.py               # Main Python firmware script (The core brain)
├── commands.json         # Dynamic keymap configuration profile
└── animation.pbm         # 128x64 compiled monochrome flipbook image strip
