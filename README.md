This is a classic Snake game implemented in Python using the Pygame library. The player controls a snake that grows longer as it eats food, and the goal is to avoid crashing into walls or the snake's own body. The game provides the option to start over after a loss or quit the game.
Requirements
Python 3.x
Pygame library
You can install the Pygame library using pip:
pip install pygame
How to Play
The game window will appear once you run the game.
The player controls the snake using the arrow keys:
Left Arrow: Move Left
Right Arrow: Move Right
Up Arrow: Move Up
Down Arrow: Move Down
The objective is to eat the red food that appears on the screen. Each time the snake eats a piece of food, it grows in length.
The game ends when the snake crashes into the walls or its own body.
After losing, you have the option to press "C" to play again or "Q" to quit the game.
Features
The snake grows longer each time it eats food.
The game detects when the snake collides with the wall or its own body, ending the game.
Display of the current score.
Option to restart the game or quit after a loss.
How to Run the Game
Clone or download the repository to your local machine.

Ensure Python 3.x is installed.

Install the Pygame library using pip install pygame.

Code Explanation
pygame.init(): Initializes all Pygame modules.
game_start(): The main function that handles the game loop and game-over scenarios.
make_snake(): Function to draw the snake on the screen.
final_score(): Displays the final score at the top of the game screen when the game ends.
display_msg(): Displays messages (like "YOU LOST!") on the screen.
timer.tick(): Controls the speed of the snake by limiting the frame rate.
