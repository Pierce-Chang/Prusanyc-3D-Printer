# Custom 3D Printer Setup with Klipper Firmware

## Overview
This README documents the custom setup of a 3D printer, combining elements from the Anycubic i3 Mega S and Prusa MK3s, with significant modifications to the internal parts and custom firmware. The printer is controlled via a Raspberry Pi server, allowing for remote operation from various devices, including mobile phones.

## Hardware Configuration
- **Base Printer**: Anycubic i3 Mega S / Prusa MK3S Hybrid
- **Changed Parts**: 
  - BIGTREETECH SKR 3 EZ Mainboard
  - Noctua Fans
  - 2x Mosfets for electrical safety (extruder and heatbed)
  - Better power supply
  - Addet Klipper Screen with Raspberry Pi 7inch screen
  - removed the default unused display and placed a noctua 40x40 fan with own created adapter in.
  - Added SUPER PINDA Probe from Prusa
  - Changed default heatbed with aluminum cnc milled plate, added magned foil on top to lay down fast changeable spring steelplate with FR4 Plate glued on it.
  - Changed heavy default steel Y axis carrier to a leightweight aluminum more thicker and stable one.
  - Changed the defaut x gantry rods to high precisions alloyed ones.
  - Added custom x and y belt tensioner.
  - Removed the springs from carrier to get a fixed postition with less vibrations.
- **Controller**: Raspberry Pi (Model: [Pi 4B 8GB])

## Firmware Configuration
- **Firmware**: Klipper

## Conclusion
This custom 3D printer setup provides a versatile and powerful printing solution, enhanced by the flexibility of Klipper firmware and remote access capabilities.
