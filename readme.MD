## Abstract 
###### 2048 is a single-player puzzle game created in March 2014, which is massively popular on both the android and the iOS platforms.
###### To implement the game on the Nexys 4 Artix 7 FPGA, we have utilised the Xilinx ISE software and the Xilinx PlanAhead tool.

## How to play?
###### The game consists of 3 stages,
###### - Obtaining the input from the user
###### - Processing the input on the FPGA
###### - Sending the corresponding output to the VGA display
###### The VGA with a resolution of 1280 x 1066 requires a refresh rate of 108Mhz. Since the onboard clock on the FPGA is of 100MHz, we utilised the IP core generator to generate a component which gives the 108MHz clock output for a 100Mhz input. The user is given an option to move the tiles on the screen in 4 directions (left, right, down and up). He controls the direction of movement based on 2 control switches on the board. 

## Where is the code?
###### The code is currently hidden, if you would like access to it please contact me on my ASU email, or any one of my teammates who helped me make this project. 

## Team composition 

- Rounak Sengupta
- Siddharth Shukla
- Gautamdev Chowdary
