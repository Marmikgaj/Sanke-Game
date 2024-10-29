Snake Game
A Python implementation of the classic Snake Game using the Pygame library. The game challenges players to control a growing snake as it consumes food, increasing in length and score while avoiding collisions.

Overview
This project recreates the nostalgic Snake game with responsive controls and modern graphics. The game runs smoothly and offers a continuous score display, making it easy for players to track their progress in real-time.

Features
Interactive Gameplay: Use arrow keys to navigate the snake in four directions.
Score Tracking: Real-time score display, which increases with each food item consumed.
Dynamic Game Over Screen: Displays the final score before closing the game.
Simplified UI: Minimalistic design focused on clean gameplay.
Gameplay Instructions
Controls:
Arrow keys control the snake:
1.Up - Move up

Down - Move down
Left - Move left
Right - Move right
Objective: Consume food blocks to grow the snake and increase the score.
Game Over Conditions:
The game ends when the snake collides with the window boundaries or with itself.
Code Structure
Event Handling: Captures and interprets arrow key inputs to control the snake’s direction.
Collision Detection: Triggers game-over state upon collision with walls or the snake’s body.
Score Display: Displays the player’s score continuously at the top of the game window.
Game Loop: A smooth, optimized game loop ensures consistent gameplay and frame rate.

Acknowledgments
This project is inspired by the original Snake game, built to showcase Python and Pygame capabilities while retaining the simplicity of the classic game.
