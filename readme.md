# SYZYGY PCB Templates

This repository contains schematics, PCB files and part libraries to use as a template for creating SYZYGY compliant peripherals. 

[More Information About SYZYGY](https://syzygyfpga.io/)

<img src="KiCAD/SZG-TEMPLATE-STD/images/BoardBottom.PNG?raw=true" width="300">

## Template Contains

* SYZYGY Standard and Transceiver Connectors
* MCU for SYZYGY DNA Support
* Programming Connector (Tag-Connect)
* Standard Mechanical Configuration (Board length can be adjusted as necessary)

## Tag-Connect Programming Header

The programming connection for the SYZYGY DNA MCU uses a connector-less [Tag-Connect header](https://www.tag-connect.com/). A wired connector with spring loaded contacts clips onto the board and connects to the headers exposed pads. The templates header design allows a programming connection from either side of the board.

The template boards support either the TC2030 or TC2030-NL. The exact cable model will depend on the programmer you are using (Changes the pinout and connector on the other end of the cable).
