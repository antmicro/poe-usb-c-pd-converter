# Power over Ethernet to USB-C Power Delivery Adapter 

Copyright (c) 2024-2025 [Antmicro](https://www.antmicro.com)

![](/img/poe-usb-c-adapter-render.png)

## Overview

This project contains open hardware PCB design files for an adapter that splits a Power-over-Ethernet (PoE) capable RJ45 interface port into a USB-C Power Delivery (PD) port and an Ethernet RJ45 port. 
It negotiates power from PoE Power Sourcing Equipment (PSE) such as a PoE switch or a PoE injector.
For the USB-C connection, the board serves as an Upstream Facing Port (UFP) power source.
The USB-C port can be used for reading current and voltage negotiated for the PD.

## Key features

* RJ45 input port for data and PoE++ (IEEE 802.3bt)
* RJ45 output port passing raw Ethernet data from the input port
* USB-C regular connector with Power Delivery feature and USB data downstream
* Automatic input power negotiation (up to 71W) from PSE
* Externally programmable flash memory
* Programmable USB Power Delivery power profiles up to 60W
* On-board VBUS voltage, current and power measurement circuitry
* On-board external fan driver with a 4-pin standard receptacle
* 112 x 56 mm (4.4 x 2.2 inch) mechanical outline

## Project structure

The main directory contains KiCad PCB design files, a LICENSE and a README.
The remaining files are stored in the following directories:
* `img` - contains graphics for this README

## License
 
This project is published under the [Apache-2.0](LICENSE) license.
