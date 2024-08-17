# Turtle Crossing Game
This project is a simple "Turtle Crossing" game built using Python's Turtle Graphics module. The player controls a turtle that must cross a busy road filled with moving cars. The goal is to reach the top of the screen without getting hit by a car. Each time the player reaches the finish line, the game becomes more challenging as the cars move faster.

# Features
# Player Control:
Use the "Up" arrow key to move the turtle northwards.
# Randomly Generated Cars: 
Cars of different colors are randomly generated and move from the right to the left side of the screen.
# Collision Detection: 
The game checks if the turtle collides with any car. If a collision occurs, the game ends.
# Level Progression: 
Each time the turtle reaches the top of the screen, the level increases, and the cars move faster.
# Scoreboard:
A scoreboard keeps track of the player's current level.
# How to Play
# Start the game:
Run the main.py file.
# Move the turtle:
Press the "Up" arrow key to move the turtle upwards.
# Avoid cars:
Navigate through the moving cars to reach the top of the screen.
# Progress through levels: 
Each time you reach the top, the game gets harder as the cars move faster.
# Game Over: 
If a car hits the turtle, the game ends.
# Project Structure
main.py: The main game loop where the game logic is executed.
player.py: Contains the Player class, which controls the turtle's movement.
car_manager.py: Contains the CarManager class, responsible for generating and moving the cars.
scoreboard.py: Contains the Scoreboard class, which handles the game's scoring and level display.
# Example Gameplay
Here's what happens during the game loop:

Cars are generated every 6th iteration and move from right to left.
The turtle moves up the screen with each "Up" arrow key press.
If the turtle collides with a car, the game ends, and "Game Over" is displayed.
If the turtle reaches the finish line at the top, the level increases, and the cars move faster.
# Contributing
If you'd like to contribute to this project, feel free to fork the repository and submit a pull request with your improvements or new features.

# License
This project is licensed under the MIT License. See the LICENSE file for details.

# Acknowledgments
Python's Turtle Graphics module for providing the tools to create this game.
The online Python community for inspiration and resources.
