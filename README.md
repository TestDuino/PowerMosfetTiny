# PowerMosfetTiny
Simple single MOSFET driver for controlling the heating bed and hot ends. Tested up to 30 amps, but capable of controlling even more. Very low RDSon (typically 500 micro ohm) allows for minimizing the size of the PCB and the heatsink 


## Connection
Connection:
* GND signal to GND of control board
* CTRL singal to 18-26 VDC control signal - in most cases connect to positive output from mosfet on control board
* SUPPLY + and - to supply Voltage - 10-30 VDC
* OUTPUT + and - to heater bed or hot end

**Please pay special attention to the power supply polarity!**
## Images

### Links
SQJQ160E-T1 datasheet | https://www.vishay.com/docs/63059/sqjq160e.pdf