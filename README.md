Created with ALTIUM Version -2017

Board specification :
There are two microcontrollers placed on the board, ATMEGA328P and ATMEGA16U2.
1x ATMEGA328P
FLASH: 32kB / EEPROM: 1kB / RAM: 2kB
Clock: 16MHz (for +5V) / 10MHz (for +3.3V)
Up to 20 input / output pins from which: 
20x digital input/output
6x PWM output
6x Analog inputs (10bit AD)
1x Serial port, 1x SPI, 1x I2C
1x User LED
1x User Buton, 1x Reset Button

1x ATMEGA16U2
FLASH: 16kB / EEPROM: 512B / RAM: 512B
Clock: 16MHz (for +5V) / 8MHz (for +3.3V)
4x Digital input / output
2x User LED
1x USB
1x SPI
1x Serial port (shared with 328P)
DFU programming support
AVRISP MKII firmware available

And 
ATMEGA328P can be programmed from ATMEGA16U2
SPI programming support
dWire debugging support
On board +3.3V / 1.5A regulator
Optional: Selection between +3V3 or +5V IO voltage
Size: 2.7 x 2.1 inch (68.6 x 53.4 mm)
Power input: micro USB or soldered wires
Power voltage: +5V (from PC, tablet & mobile phone charger or an external power supply)


Improved funtionalities:


 Reset improvement
Both RESET pins ( 16U2 and 328P ) are now driven through an open drain buffer. This means: improved RESET quality and it adds an option to debug the microcontrollers through dWire.

 3.3V and 5V Support
If you would like to connect 28Pins to a board with 3.3V pins, you can. We added an option to switch between 5V or 3.3V pin voltage. Simply, just change the JP4 jumper.

 Use it as a Programmer
ATMEGA16U2 can now be used as an universal AVRISP MKII programmer. Once you change the firmware, you can use it to program the onboard ATMEGA328P or any other board.

 Other
Micro USB (use any mobile phone or tablet charger to power the board), User Button added, DFU Disable jumper, dWire debugger (if correct firmware is used, 16U2 can work as an dWire debugger).
Raw project : link
