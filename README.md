# USB Payload with Raspberry Pi Pico

## Overview

This project is designed for educational purposes to demonstrate the potential risks associated with USB devices and to teach cybersecurity concepts. This payload script is written in Ducky Script. When put on a Raspberry Pi Pico's root(with the necessary configuration described [here](https://github.com/dbisu/pico-ducky)). When plugged into a computer, pico performs a series of automated actions. Specifically, it opens the terminal, downloads, and installs Unified Remote, and allows remote control of the computer.

## Requirements

- **Hardware**:
  - Raspberry Pi Pico
  - USB cable

- **Software**:
  - CircuitPython
  - adafruit libraries
  - Unified Remote application on phone

## Installation

1. **Set up Raspberry Pi Pico**:
   - Refer to [here](https://github.com/dbisu/pico-ducky)

2. **Upload the Script**:
   - copy the payload.dd into the root of pico

## Usage

1. **Insert the USB**:
   - Plug the Raspberry Pi Pico into the target computer.

2. **Payload Execution**:
   - The payload script will execute automatically.
   - The terminal will open, and the Unified Remote server will be downloaded and installed.

3. **Remote Control**:
   - Connect to the target computer using the Unified Remote app on your smartphone or another device.
   - Control the computer remotely.
  
## Disclaimer

This project is intended solely for educational use.
