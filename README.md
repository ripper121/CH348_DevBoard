# CH348 DevBoard

[![CH348L_PCB_TOP.png](https://github.com/ripper121/CH348_DevBoard/raw/main/CH348L_PCB_TOP.png "CH348L_PCB_TOP.png")](https://github.com/ripper121/CH348_DevBoard/blob/main/CH348L_PCB_TOP.png "CH348L_PCB_TOP.png")

[![CH348L_PCB_TOP.png](https://github.com/ripper121/CH348_DevBoard/raw/main/CH348L_PC_ISO.png "CH348L_PC_ISO.png")](https://github.com/ripper121/CH348_DevBoard/blob/main/CH348L_PC_ISO.png "CH348L_PC_ISO.png")

[![CH348L_PCB_TOP.png](https://github.com/ripper121/CH348_DevBoard/raw/main/CH348L_PCB_BOTTOM.png "CH348L_PCB_BOTTOM.png")](https://github.com/ripper121/CH348_DevBoard/blob/main/CH348L_PCB_BOTTOM.png "CH348L_PCB_BOTTOM.png")

###Features:
- USB-C Connector
- USB ESD Protection
- 500mA Polyfuse (self resettable fuse)
- Leds:
 - RX shows data receiving status
 - TX shows data transmitting status
 - ACT shows USB configuration completed status
- Jumpers
 - CFG: During power-on, if the CFG pin is
at a high level or not connected, all DTRx/ TNOWx pins
are configured to function as TNOW. CFG pin is low, all
DTRx/ TNOWx pins are configured for DTR function.
- VIO: The power supply of RTS0, CTS0, DTR4, DTR5, DTR6 and DTR7 pins of CH348L come from VCC,
these pins are 3.3V signal level. The power supply of other UARTs and MODEM signal pins come
from VIO, which are 3.3V/2.5V/1.8V matching VIO signal level.
- JST PH 2.0mm 10 Pin Connectors for the UART Pins
 - 3V3, GND, RXD, TXD, RTS, CTS, DTR, DSR, DCD, RI
- Size 100 x 80 mm
- 3.2 mm mounting holes

[CH348 Datasheet](https://github.com/ripper121/CH348_DevBoard/blob/main/CH348DS1.PDF "CH348 Datasheet")


If you want to order one assembled PCB: [Contact Me](https://ripper121.com/contact/ "Contact Me")
