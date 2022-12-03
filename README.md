# Bloop Box Hardware

[![ci](https://github.com/bloop-box/bloop-box-hardware/actions/workflows/ci.yml/badge.svg)](https://github.com/bloop-box/bloop-box-hardware/actions/workflows/ci.yml)

All boards are designed using KiCAD 6 with production and assembly by JLCPCB (not a sponsor) in mind. All parts were selected to be available from JLCPCB at the time of creating these boards with as many parts used from their basic library as possible.

The hardware is published under the [CERN Open Hardware Licence Version 2 - Permissive](LICENSES/CERN-OHL-P-2.0.txt)

## Mainboard

- uHAT format (fits on a Raspberry Pi Zero)
- Connectors for:
  - Tailboard (Power supply, buttons, LEDs)
  - SPI NFC-reader (Pinout fitting for *PN532 V3* Module)
  - Speaker
  - RGB-LED or LED-Board
  - I2C (optional) with either 3.3V or 5V (set through solder jumper)
  - Additional GPIO header (optional)
- Speaker is driven by a MAX98357 3W amplifier
  - amplifier gain can be set through jumper (9dB default setting)
  - SD_MODE is set to stereo mix by default, solder jumper for setting left-only 

Pinout of all connectors is printed on the bottom of the board

See schematics for detailled GPIO pinout

The board fulfills all specifications for a uHAT but has no ID EEPROM to save cost

## Tailboard

- two power inputs
  - 5.5x2.1mm barrel-jack
  - USB-C with PowerDelivery support
- Can handle 5V and 8 to 28V inputs 
- Can deliver 5V with up to 3A to the mainboard (assuming it gets enough power)
- Additional circuitry to prevent damage in case two power supplies are connected
- Two buttons connected to the Raspberry Pi, per default used for volume control
- Three LEDs to show status of power supply, can also be remote-controlled by Raspberry Pi through the Mainboard

Firmware for the PD-Controller will be published once it's ready

An additional, simpler Tailboard that only has 5V input is planned 

## LED-Board

Allows the RGB LED to be mounted independent of the Mainboard
