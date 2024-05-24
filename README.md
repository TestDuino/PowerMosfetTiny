# PowerMosfetTiny
Simple single MOSFET driver for controlling the heating bed and hot ends. Tested up to 30 amps, but capable of controlling even more. Very low RDSon (typically 500 micro ohm) allows for minimizing the size of the PCB and the heatsink 

## PCB manufacturing
Schematics, gerbers and Bill of Materials (BOM) are available under *Electronic Design* directory. PCBs can be oredered on JLCPCB or any other PCB manufacturer. It is recommended to buy components from reliable sources like Mouse, Farnell, Digikey, TME. All symbols and footprints on the schematics was acquired from mouser page.

## Connection
Connection:
* GND signal to GND of control board
* CTRL singal to 18-26 VDC control signal - in most cases connect to positive output from mosfet on control board
* SUPPLY + and - to supply Voltage - 10-30 VDC
* OUTPUT + and - to heater bed or hot end

**Please pay special attention to the power supply polarity!**
## Images
![PCB view](https://github.com/TestDuino/PowerMosfetTiny/blob/main/Images/PowerMosfetTidy_OrtoView.png)
![TOP view](https://github.com/TestDuino/PowerMosfetTiny/blob/main/Images/PowerMosfetTidy_TopView.png)
![SIDE view](https://github.com/TestDuino/PowerMosfetTiny/blob/main/Images/PowerMosfetTidy_SideView.png)

# Contributions
If you find any bugs, have suggestions, or would like to contribute to the development of this project, feel free to contact me or submit a pull request (PR). Your contributions are greatly appreciated, and I am always open to feedback and collaboration. Thank you for helping to improve this project!

### Links
SQJQ160E-T1 datasheet | https://www.vishay.com/docs/63059/sqjq160e.pdf