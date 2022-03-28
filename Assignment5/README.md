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

![This is an image](https://github.com/Hlederma/CPE-487/blob/54f327ab22e72bae1de77a54648b9438b58dbea0/Assignment5/Ball_imp_unmodified.png)


The video below shows a red square bouncing ball moving vertically running on the Nexys A7 board displayed on the monitor.



https://user-images.githubusercontent.com/70532894/160458128-ccd7009e-b2fd-4085-a1a7-0787015e80db.MOV





## Project 2: Modified Bouncing Ball
The implemented design of the circuit in Vivado is shown in the image below.

![This is an image](https://github.com/Hlederma/CPE-487/blob/c06d76a8b565fa459bee071028243784568cc3ac/Assignment5/Ball_imp_modified.png)

The video below shows a light blue circular bouncing ball moving vertically and horizontally running on the Nexys A7 board displayed on the monitor.




https://user-images.githubusercontent.com/70532894/160459453-eddfe786-1fcc-4254-aa73-69875522c552.MOV



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

## Project 1: Video Game PONG
The implemented design of the circuit in Vivado is shown in the image below.

![This is an image](https://github.com/Hlederma/CPE-487/blob/6bb6d537dd01008693de078c9023e48d4166ea10/Assignment5/Pong_imp_unmodified.png)

The video below shows a light blue rectangle moving horizontally running on the Nexys A7 board displayed on the monitor. Pressing the BTNC button on the board will start the game with a red ball traveling up and bouncing at the edge of the screen. The objective of the game is to hit the ball against the rectangle by twisting the knob on the potentiometer. The game ends when the ball is dropped.



https://user-images.githubusercontent.com/70532894/160466809-17b70f24-5b8f-4071-960b-35b76f60ac3b.mov




## Project 2: Modified Video Game PONG
The implemented design of the circuit in Vivado is shown in the image below.

![This is an image](https://github.com/Hlederma/CPE-487/blob/ed9a69889ef4459bf302bb725d92e6cf4c8e0317/Assignment5/Pong_imp_modified.png)

The video below shows a light blue rectangle moving horizontally running on the Nexys A7 board displayed on the monitor. The width of the rectangle has been doubled and the count of successful hits is now displayed on the board 7-Segment LED. The ball speed can be modified by using switches SW0 - SW4.






https://user-images.githubusercontent.com/70532894/160489886-450f5d39-876a-4f29-8199-90bcc2e23185.mov


