# MAZE_game

# MAZE_game

A fun and interactive maze game where players use a joystick to navigate through a maze displayed on an OLED screen. This project is built using an Arduino Uno/Nano microcontroller and an OLED display to create a simple yet engaging game.

About->
Maze Game is a simple game developed using an Arduino Uno/Nano, a Joystick, and an OLED screen. The player controls a cursor on the OLED screen using the joystick, attempting to navigate through the maze and reach the goal without hitting the walls. The game is fully interactive and provides an immersive way to explore basic game development with embedded systems.

Components Used->
This project requires the following components:
Arduino Uno: The main microcontroller for controlling the game logic.
OLED Display (128x64): Displays the maze and player’s movement.
Joystick Module: Used to control the movement of the player within the maze.
Jumper Wires and Breadboard (for connecting components).

Installation & Setup->
To set up the project, follow these steps:
Connect the Components:
Connect the OLED display to the Arduino Uno/Nano.
VCC -> 5V
GND -> GND
SDA -> A4
SCL -> A5

Connect the Joystick to the Arduino Uno/Nano.
VCC -> 5
GND -> GND
VRX -> A1
VRY -> A0
SW -> Digital Pin (e.g., D2)

Upload the Code to Arduino:
Open the Arduino IDE and load the provided sketch (maze_game.ino).
Select the correct board (Arduino Uno/Nano) and the correct port.
Upload the sketch to your Arduino Uno/Nano.
Power the Circuit:
Power your Arduino Uno/Nano using a USB cable or an external power source.
Your maze game should now be running on the OLED screen!

Game Instructions->
Start the Game:
The game will start automatically when the Arduino is powered on or reset.
Control the Player:
Use the Joystick to navigate through the maze:
Move Up or Down using the vertical axis.
Move Left or Right using the horizontal axis.
Objective:
Navigate from the Spawn point to the Goal point (Arrow marked).

Contributing->
If you’d like to contribute to this project, feel free to fork the repository and submit a pull request. Here are a few things you could work on:
Improve maze generation algorithm
Add sound effects or beeping for player actions.
Design new levels with increasing difficulty.
Enhance the player controls or game logic.

thanks :)
