# CH348 DevBoard
### USB to Octal Serial / Uart ports

[![CH348L_PCB_TOP.png](https://github.com/ripper121/CH348_DevBoard/raw/main/Images/CH348L_PCB_TOP.png "CH348L_PCB_TOP.png")](https://github.com/ripper121/CH348_DevBoard/blob/main/Images/CH348L_PCB_TOP.png "CH348L_PCB_TOP.png")

[![CH348L_PCB_TOP.png](https://github.com/ripper121/CH348_DevBoard/raw/main/Image/CH348L_PCB_ISO.png "CH348L_PC_ISO.png")](https://github.com/ripper121/CH348_DevBoard/blob/main/Images/CH348L_PC_ISO.png "CH348L_PCB_ISO.png")

[![CH348L_PCB_TOP.png](https://github.com/ripper121/CH348_DevBoard/raw/main/Image/CH348L_PCB_BOTTOM.png "CH348L_PCB_BOTTOM.png")](https://github.com/ripper121/CH348_DevBoard/blob/main/Images/CH348L_PCB_BOTTOM.png "CH348L_PCB_BOTTOM.png")

###Features:
- No drivers needed for Winows and Linux
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

###### From Datasheet:
- 480Mbps high-speed USB device interface, peripheral components only need crystal oscillator and capacitors
- Built-in firmware, emulate standard UART interface, used to upgrade the original serial peripheral or expand additional UART via USB
- Original serial applications are totally compatible without any modification in Windows operating systems
- Hardware full duplex UART interface, integrated independent transmit-receive buffer, supports communication baud rate varies from 1200bps to 6Mbps
- UART supports 8 data bits, supports odd, even, and none parity, supports 1 or 2 stop bits
- Integrated the 2048-byte RX FIFO and 1024-byte TX FIFO for each UART
- Supports common MODEM signals RTS, DTR, DCD, RI, DSR and CTS
- Supports CTS and RTS hardware automatic flow control
- Supports half-duplex, provides sending status TNOW, used for controlling RS485 to transmit-receive switch
- Supports up to 48-channel GPIO input and output function
- Supports RS232/RS485/RS422 interface, through external voltage conversion chip
- Built-in EEPROM used to configure the chip of VID, PID, maximum current value, vendor and product information string, etc


[CH348 Datasheet](https://github.com/ripper121/CH348_DevBoard/blob/main/CH348DS1.PDF "CH348 Datasheet")

[Driver & Software](http://www.wch-ic.com/search?q=CH348&t=downloads "Driver & Software")


If you want to order one assembled PCB: [Contact Me](https://ripper121.com/contact/ "Contact Me")
