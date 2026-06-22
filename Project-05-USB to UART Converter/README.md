Overview

This project is a USB Type-C to UART Converter designed using the CP2102N USB-to-UART Bridge Controller.
It enables communication between a computer and microcontrollers, development boards, or embedded systems through a standard UART interface.
The board uses a USB Type-C connector for power and data transfer and exposes UART signals through external header pins.

Features
USB Type-C Interface
CP2102N USB-to-UART Bridge
UART Communication (TX/RX)
Reset Signal Access
Compact and Easy-to-Use Design
Plug-and-Play USB Connectivity
Suitable for Embedded Development and Debugging
Components Used
CP2102N USB-to-UART Bridge IC
USB Type-C Connector
Status LEDs
Decoupling Capacitors
Pull-up/Pull-down Resistors
UART Header Connector
PCB Designed in KiCad
Pin Configuration
Pin	Description
VBUS	+5V USB Supply
GND	Ground
TX	UART Transmit
RX	UART Receive
RST	Reset Signal
Working Principle
The USB Type-C connector receives power and USB data from the host computer.
The CP2102N enumerates as a virtual COM port on the operating system.
USB data is converted into UART serial data.
The TX and RX pins provide serial communication with external microcontrollers or embedded devices.
Status LEDs indicate power and communication activity.
Applications
Microcontroller Programming
Serial Debugging
Embedded System Development
Firmware Uploading
IoT Prototyping
UART Communication Testing
