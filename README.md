# Ping Pong Ball Game using Arduino Uno ON TinkerCad

## Overview
This project implements a classic ping-pong game on an LCD display using Arduino Uno. Two players control paddles with push buttons to hit a ball back and forth. The game features score tracking, visual feedback with NeoPixel LEDs, and sound effects via a piezo buzzer. The project demonstrates real-time interaction, game logic, and hardware integration with Arduino.

## Features
- **2-Player Gameplay**: Each player controls a paddle using UP/DOWN buttons.
- **Score Tracking**: Real-time score display on the LCD.
- **Visual Feedback**: NeoPixel LEDs glow green for the winner and red for the loser.
- **Sound Effects**: Piezo buzzer signals game events (e.g., scoring, game over).
- **Dynamic Ball Movement**: Ball changes direction and speed based on paddle hits.
- **Reset Functionality**: Game restarts automatically after a player wins.

## Components Used
- Arduino Uno
- 16x2 LCD Display
- 2x NeoPixel LEDs
- 5x Push Buttons (for paddles and start/pause)
- Piezo Buzzer
- Breadboard and Jumper Wires
- 5x 220Ω Resistors
- Potentiometer (for LCD contrast)

## Setup Instructions
1. **Hardware Assembly**:
   - Connect the LCD, push buttons, NeoPixel LEDs, and piezo buzzer to the Arduino as per the circuit diagram.
   - Use the potentiometer to adjust LCD contrast.

2. **Upload the Code**:
   - Copy the provided Arduino sketch into the IDE.
   - Upload the code to the Arduino Uno.

3. **Start the Game**:
   - Power the Arduino.
   - Press the "Start" button to begin the game.
   - Use the UP/DOWN buttons to move paddles.

## How to Play
- **Player 1**: Uses buttons connected to pins 6 (UP) and 7 (DOWN).
- **Player 2**: Uses buttons connected to pins 8 (UP) and 9 (DOWN).
- **Objective**: Hit the ball with your paddle. If you miss, the opponent scores a point.
- **Winning**: The first player to miss the ball loses, and the game resets.

## Output Screenshots
- **Initial Screen**: Displays "Arduino UNO Ping Pong Game" and developer name.  
- **Gameplay**: Shows scores, paddles, and moving ball.  
- **Game Over**: Announces the winner and triggers LED feedback.

## Video Tutorial
Watch the project in action: [YouTube Demo](https://youtu.be/-dlXmIlm654)

## Code Explanation
The Arduino sketch uses:
- **LiquidCrystal Library**: To control the LCD display.
- **Adafruit_NeoPixel Library**: For LED feedback.
- **Custom Functions**: To handle paddle movement, ball physics, scoring, and sound effects.

## Troubleshooting
- **LCD Not Displaying**: Adjust the potentiometer for contrast.
- **Buttons Unresponsive**: Check wiring and resistor connections.
- **No Sound**: Verify the piezo buzzer is connected to pin 10.

## License
This project is open-source. Feel free to modify and distribute it.  

**Enjoy the game!** 🏓  
