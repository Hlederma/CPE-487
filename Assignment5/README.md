# Lab 3: Bouncing Ball

## VHDL Files
### Bouncing Ball
* Ball: [ball.vhd](./ball.vhd)
* Clocking Wizard: [clk_wiz_0.vhd](./clk_wiz_0.vhd)
* Clocking Wizard Architecture: [clk_wiz_0_clk_wiz.vhd](./clk_wiz_0_clk_wiz.vhd)
* VGA Sync: [vga_sync.vhd](./vga_sync.vhd)
* VGA Top: [vga_top.vhd](./vga_top.vhd)

### Modified Bouncing Ball
* Ball: [ball_1.vhd](./ball_1.vhd)
* Clocking Wizard: [clk_wiz_0.vhd](./clk_wiz_0.vhd)
* Clocking Wizard Architecture: [clk_wiz_0_clk_wiz.vhd](./clk_wiz_0_clk_wiz.vhd)
* VGA Sync: [vga_sync.vhd](./vga_sync.vhd)
* VGA Top: [vga_top.vhd](./vga_top.vhd)

## Constraint Files
* Bouncing Ball: [vga_top.xdc](./vga_top.xdc)

## Project 1: Bouncing Ball
The implemented design of the circuit in Vivado is shown in the image below.

![This is an image]()


The video below shows a red square bouncing ball moving vertically running on the Nexys A7 board displayed on the monitor.





## Project 2: Modified Bouncing Ball
The implemented design of the circuit in Vivado is shown in the image below.

![This is an image]()

The video below shows a light blue circular bouncing ball moving vertically and horizontally running on the Nexys A7 board displayed on the monitor.




# Lab 6: Video Game PONG

## VHDL Files
### Video Game PONG
* Analog to Digital Converter: [adc_if.vhd](./adc_if.vhd)
* Bat and Ball: [bat_n_ball.vhd](./bat_n_ball.vhd)
* Clocking Wizard: [clk_wiz_0.vhd](./clk_wiz_0.vhd)
* Clocking Wizard Architecture: [clk_wiz_0_clk_wiz.vhd](./clk_wiz_0_clk_wiz.vhd)
* PONG: [pong.vhd](./pong.vhd)
* VGA Sync: [vga_sync.vhd](./vga_sync.vhd)

### Modified Video Game PONG
* Analog to Digital Converter: [adc_if.vhd](./adc_if.vhd)
* Bat and Ball: [bat_n_ball_1.vhd](./bat_n_ball_1.vhd)
* Clocking Wizard: [clk_wiz_0.vhd](./clk_wiz_0.vhd)
* Clocking Wizard Architecture: [clk_wiz_0_clk_wiz.vhd](./clk_wiz_0_clk_wiz.vhd)
* LED Decoder 16 bit: [leddec16.vhd](./leddec16.vhd)
* PONG: [pong_1.vhd](./pong_1.vhd)
* VGA Sync: [vga_sync.vhd](./vga_sync.vhd)

## Constraint Files
* PONG: [pong.xdc](./pong.xdc)
* Modified PONG: [pong_1.xdc](./pong_1.xdc)

## Required Hardware
* Pmod AD1
* Potentiometer Controller
* Monitor with VGA connector

## Project 1: Video Game PONG
The implemented design of the circuit in Vivado is shown in the image below.

![This is an image](https://github.com/Arif12467/Digital-System-Design-AIA/blob/c7a903e82e497ea5a9273f97d2a5677c1545e14d/Assignment-5/implemented_design_2.png)

The video below shows a light blue rectangle moving horizontally running on the Nexys A7 board displayed on the monitor. Pressing the BTNC button on the board will start the game with a red ball traveling up and bouncing at the edge of the screen. The objective of the game is to hit the ball against the rectangle by twisting the knob on the potentiometer. The game ends when the ball is dropped.

https://user-images.githubusercontent.com/78330724/156935671-ef2b3fc2-828b-41ce-8281-b94dbcf4b628.mp4



## Project 2: Modified Video Game PONG
The implemented design of the circuit in Vivado is shown in the image below.

![This is an image](https://github.com/Arif12467/Digital-System-Design-AIA/blob/c7a903e82e497ea5a9273f97d2a5677c1545e14d/Assignment-5/implemented_design_3.png)

The video below shows a light blue rectangle moving horizontally running on the Nexys A7 board displayed on the monitor. The width of the rectangle has been doubled and the count of successful hits is now displayed on the board 7-Segment LED. The ball speed can be modified by using switches SW0 - SW4.

https://user-images.githubusercontent.com/78330724/156935785-44e29fb9-f66c-4a4a-9753-d0d750b28ea8.mp4

