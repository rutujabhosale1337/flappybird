 Flappy Bird Python Clone
A faithful recreation of the viral mobile hit, built using *Python* and the *Pygame* library. This project demonstrates basic game physics, collision detection, and sprite animation.


##  Features
 * *Physics-based Gameplay:* Realistic gravity and "flap" mechanics.
 * *Procedural Obstacles:* Randomized pipe heights for endless gameplay.
 * *Score Tracking:* Real-time scoring system with high-score persistence.
 * *Sound Effects:* Classic 8-bit style audio for jumping and crashing.
##  Installation
### Prerequisites
 * Python 3.x
 * Pip (Python package manager)
### Setup

   
   
 *Install dependencies:*
   bash
   pip install pygame
   
   
 *Run the game:*
   bash
   python main.py
   
   
##  How to Play
The objective is simple: fly the bird as far as you can without hitting the pipes or the ground.
| Action | Input |
|---|---|
| *Flap/Jump* | Spacebar or Left Click |
| *Restart Game* | R Key (after Game Over) |
| *Quit* | Esc or Close Window |
##  Project Structure
 * main.py: The entry point of the game containing the main loop.
 * assets/: Directory containing images (.png) and sounds (.wav).
 * sprites.py: (Optional) Classes for the Bird and Pipe objects.
 * constants.py: Game configurations like screen width, height, and gravity constants.
##  Mathematical Logic
The bird's movement is governed by a simple Euler integration for vertical motion:
Where:
 * g is the gravity constant.
 * v is the vertical velocity.
 * y is the vertical position on the screen.
##  License
Distributed under the MIT License. See LICENSE for more information.
##  Acknowledgments
 * Original game by Dong Nguyen.
