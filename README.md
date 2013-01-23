chipper
=======

Open Source universal device programmer H/W and S/W

The aim of this project is to create h/w and S/w for an universal device programmer,

The programmer s/w will be written using QT 5.0 and libusb to support multiplatform OSX, Linux and Windows development. It will also reuse the qhexedit control for data buffer handling.

The h/w will be a true universal 48 pin driver that supports VSS, VCCX 1.2v – 6.5v, VPP 5v – 25v and data or address on any given pin, an fpga will be used to mux the data and address bus pins from an MCU.
The MCU will be a 32 bit arm processor that supports DFU from boot code in ROM, hence it should be programmable without a programmer.


