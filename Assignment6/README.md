# Lab 4: Hex Calculator

## VHDL Files
### Hex Calculator
* Hex Calculator: [hexcalc.vhd](./hexcalc.vhd)
* Keypad: [keypad.vhd](./keypad.vhd)
* LED Decoder 16-bits: [leddec16.vhd](./leddec16.vhd)
### Modified Hex Calculator
* Hex Calculator: [hexcalc_1.vhd](./hexcalc_1.vhd)
* Keypad: [keypad.vhd](./keypad.vhd)
* LED Decoder 16-bits: [leddec16_1.vhd](./leddec16_1.vhd)
## Constraint Files
* Hex Calculator: [hexcalc.xdc](./hexcalc.xdc)
* Modified Hex Calculator: [hexcalc_1.xdc](./hexcalc_1.xdc)
## Required Hardware
* Pmod KYPD
* 2x6 Pin Cable

## Project 1: Hex Calculator
The implemented design of the circuit in Vivado is shown in the image below.

![This is an image](https://github.com/Hlederma/CPE-487/blob/43a6a7cdf952bf1f0ed3b7475071299941aa9802/Assignment6/hexcalc_imp_unmodified.png)


The videos below shows the Hex Calculator running on the Nexys A7 board. Addition is performed by entering an number using the Pmod KYPD and pressing the BTNU button on the board. By pressing the BTNL button, the board displays the result on the 7-Segment LED Display. To clear the calculator, press the BTNC button, which will return the display to zero.



https://user-images.githubusercontent.com/70532894/160497573-a417b67b-8f3b-46c5-99c8-a5526d827bf8.MOV



https://user-images.githubusercontent.com/70532894/160497591-0143148c-a06a-4ec3-8349-0f2fc9083f9d.MOV



## Project 2: Modified Hex Calculator
The implemented design of the circuit in Vivado is shown in the image below.

![This is an image](https://github.com/Hlederma/CPE-487/blob/d32af41a93862f7701ed027e745263b21bd52031/Assignment6/hexcalc_imp_modified.png)

The video below shows the Modified Hex Calculator running on the Nexys A7 board. The 7-Segment LED Display now supresses the leading zero. Subtraction is performed by entering an number using the Pmod KYPD and pressing the BTND button on the board.




