# We must build 3 person pong

The intent of this fork is to make modifications and improve the replay ability of the 3 person pong game I (Mycole) developed and build on top of modifications made by my friend Charlie.  I also want to get mroe familiar with the pygame library.

## Controls
1P (RED): A, S  
2P (GREEN): Up, Down arrows  
3P (BLUE): O, L  

Quit: Esc

Score is handled by the last paddle to touch the ball when it enters a score zone gets the point. If your paddle was the last one hit and you score on your own zone, you lose a point. Game ends at 10 points

## Current Improvements

 - Adjust padding of paddle movement
 - Adjust controls and make them constants in the file for easy editing
 - Remove lines behind paddle to emphasize out of bounds
 - Create scouring system based on last paddle touched
 - End game at 10 points
 - Adjust delay before ball reset
 - Add Sound Effects
 

## To Dos

 - Game start and end UI menus
 - AI and player select options
 - Package game for widespread playability
 - Unite drawing and collision code
 - Ensure padding is consistent regardless of screen draw size

## Stretch To Dos

 - Settings menu
 - Spinning board mode
 - Paddles traverse 1/3 of the playing field
 - Analog control compatibility 
