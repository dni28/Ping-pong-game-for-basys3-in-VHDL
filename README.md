This VHDL project implements a Ping-Pong style reaction game using LEDs, buttons, and a 7-segment display on an FPGA board.
An LED “ball” moves across 16 LEDs, left or right, depending on the current state.
Players press btnL or btnR to “hit” the ball. A valid hit occurs only when the LED reaches the edge (position 0 or 15). Otherwise, it's a miss and the round resets.
Each player’s score is displayed on a 4-digit 7-segment display.
If a player hits correctly, their score increases; if they miss, all LEDs flash, and the game returns to the idle state ready for a new round.
