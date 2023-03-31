# slug-space-invaders-Verilog

## how to run
1. Make sure Vivado is installed on your device
2. Download the zip file.
3. In folder, extract the zip file, then extract the Lab 6 zip file.
4. Click on the Lab 6 Vivado Project File.
5. Once Vivado opens, click on Open Hardware Manager under the Flow Navigator, and make sure to connect to the BASTS3 board. Make sure the VGA controller is connected to a Monitor.
6. Once that is done, click on Program device.

## Description
The slug starts in the middle of the screen on the ground. The buttons on the board are used to control the movement of the slug. The slug moves at 1 pixel per frame. BtnR and BtnL stay in their location after it is pressed. BtnD moves downwards (into the ground) while it is being pressed and floats back up once it is released. 

BtnC is pressed to start the game. Once the game starts, 5 ships with random widths and random locations drop to the ground, each one second apart. Once the ship touches the ground, it stays there for one second and then releases the pink alien, which disappears 3 seconds after. The player gets one point if the slug comes in contact with the pink alien and eats it. The pink alien will flash when the slug eats the pink alien. The points will display on the 7 segment display on the board. 

The game is over once the slug comes in contact with the ship before it touches the ground. Once the game is over, the red border on the game and the slug will flash, the slug’s movement will be disabled, and all of the ships will freeze. From this state, when btnC is pressed, the game will start over. The ships will start dropping from the top, score will go to zero, and the slug will resume its position from the previous game. 
