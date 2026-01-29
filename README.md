# 4CH Relay Timer

![PCB](https://github.com/MAATHES-THILAK-K/4CH-RELAY---TIMER/blob/main/IMAGES/FRONT.png)

## Overview
ESP32-C3 based 4-channel relay controller with DS3231 RTC for timer applications. Each channel handles 10A AC loads with MOSFET input control.

## Features
- 4x 10A relays with MOSFET control
- ESP32-C3 Mini for Wi-Fi/Bluetooth
- DS3231 RTC for precise timing
- Direct AC input sensing
- Timer-based automation

## Hardware
- MCU: ESP32-C3-MINI-1
- RTC: DS3231 with battery backup
- Relays: 10A 250VAC SPDT
- Input: 5V DC
- AC sensing: Opto-isolated

## Usage
1. Power with 5V DC
2. Connect AC loads to relay outputs
3. Program via USB-C
4. Set timers via web interface

## Safety
⚠️ **HIGH VOLTAGE** - Requires proper insulation and qualified installation.

## License
Apache 2.0
