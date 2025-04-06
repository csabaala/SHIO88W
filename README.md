# SHIO88W

ESP32 based DIN rail mount IO board.

More [Pictures](/Pictures) and [Video](/ESPHome) of the assembled board and extensions.

Example [ESPHome configs](/ESPHome)

## Features

* 12V DC input for powering
* 8 open collector output (50 mA load per channel)
* 8 opto isolated input
* LEDs for output and input status
* 1 sensor input (ds18b20, dht)
* 14 pin IDC connector for direct GPIO access

## Extensions

### SHADRS485

Extension board mountable top of the SHIO88W board.

* Sockets and breakout for 2 ADS1115 AD converter
* On board voltage dividers for each channel
* RS-485 interface

### SHHMI

Control interface for SHIO88W.

* PCB for 128x64 OLED display and control buttons. Fits the 0.96 and 1.3 inch OLED versions.
* Mountable top of the SHADRS485 board
