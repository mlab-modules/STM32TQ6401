# STM32TQ6401 - Universal TQFP64 STM32 Microcontroller Module

The STM32TQ6401 is a universal microcontroller module designed for STM32 MCUs in TQFP64 packages. It offers a flexible platform for both development and deployment, with support for a wide range of STM32 devices and power configurations.

## Features

- Compatible with most STM32 MCUs in TQFP64 package (see note in schematics for exceptions)
- Direct battery operation from a CR2032 cell
- USB-C connector for both programming and external power input
- Standard MLAB pin headers for module interconnection to other MLAB modules
- Onboard 32.768 kHz and 16 MHz crystal oscillators for RTC and system clock
- Multiple LDO regulators providing 3.3V from USB or external 5V input
- USB power switch (TPS2051B) for host/device support
- Boot and reset buttons, debug header (SWD), and optional VCAP configuration

## Power Supply

- **Battery Operation:** Directly powered by a CR2032 cell; suitable for ultra-low power STM32 MCUs
- **USB Power:** Supplied through USB-C connector; LDO regulator converts 5V to 3.3V
- **External Power Input:** 2.6 V to 5.2 V via dedicated jumper or header

## Connectivity

- USB-C for firmware upload and serial communication
- SWD (Serial Wire Debug) header for in-circuit debugging
- MLAB standard headers for full I/O access

## Clock Sources

- **Y1:** 32.768 kHz crystal for RTC
- **Y2:** 16 MHz crystal for system clock

### Incompatible STM32 Devices
Some STM32 MCUs are not compatible with this module due to VCAP or other special pin requirements. These include (but are not limited to):

- STM32F030R4Tx, STM32F405RGTx, STM32H7xxRxTx
- STM32G4xxRxTx, STM32L5xxRxTxQ, STM32U5xxRxTxQ

Refer to schematic details for a complete list of incompatible devices.

### Pin Variants

Special attention is required for the following pins due to variant functions:

- VBAT / VLCD
- VCAP / VDDUSB
- BOOT0 / PH3

Refer to MCU datasheets and the module schematic for proper configuration.

## Mounting

- Four 3mm MLAB mounting holes for mechanical stability

## Schematic

For detailed pinout, power configuration, and compatibility, refer to the [STM32TQ6401A schematic](STM32TQ6401A%20Schema.pdf).


