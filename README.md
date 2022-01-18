# PBScreen-for-LOVE2D
Library for LÖVE that draws your canvas fully to the screen, stretch proof.

How to use it:

First off you'll need to require the file to a variable in your main or in any file you gonna use it
suggested variable would be a global PBScreen

PBScreen =  require "path/PBScreen
"
Then you will need to set the canvas like you normally do

After setting the canvas, you can call the method drawCanvas from the lib in order for the game canvas to fit the entire screen 
without any distortion and fully, and it should be stretch proof and support resizing.

game_canvas is the canvas you'd like to draw
game_width is your game canvas screen width
game_height is your game canvas screen height

Thank you for trying it out! I hope it helps!