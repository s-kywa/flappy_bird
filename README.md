# Flappy Bird Game

A Python implementation of the classic Flappy Bird game using Pygame. This project recreates the popular mobile game where players control a bird, navigating it through a series of pipes without touching them.

## Features

- Classic Flappy Bird gameplay
- Score tracking
- Smooth bird animation and physics
- Randomly generated pipes
- Game over and restart functionality
- Simple and intuitive controls

## Requirements

- Python 3.x
- Pygame library

## Installation

1. Clone this repository or download the source code
2. Install the required dependencies:
   ```bash
   pip install pygame
   ```

## How to Play

1. Run the game:
   ```bash
   python flappy_bird.py
   ```

2. Controls:
   - Press SPACE or UP ARROW to make the bird jump
   - Click the mouse button to make the bird jump
   - Press R or ENTER to restart the game after game over

3. Game Rules:
   - The bird will fall due to gravity
   - Press the jump button to make the bird fly upward
   - Navigate through the gaps between pipes
   - Each successful pipe pass earns you 1 point
   - The game ends if the bird hits a pipe or the ground

## Game Components

1. **Bird**
   - Animated sprite with flapping wings
   - Rotates based on vertical velocity
   - Responds to player input for jumping

2. **Pipes**
   - Randomly generated pairs of pipes
   - Move from right to left
   - Create gaps for the bird to pass through

3. **Scoring**
   - Score increases when passing through pipes
   - Score is displayed at the top of the screen

4. **Game Over**
   - Occurs when the bird hits a pipe or the ground
   - Displays a restart button
   - Allows the player to start a new game

## Project Structure

- `flappy_bird.py` - Main game file containing all game logic
- `img/` - Directory containing game assets:
  - `bird1.png`, `bird2.png`, `bird3.png` - Bird animation frames
  - `pipe.png` - Pipe obstacle
  - `ground.png` - Ground texture
  - `bg.png` - Background image
  - `restart.png` - Restart button image

## Development

This project was created using:
- Python 3.x
- Pygame for game development
- Simple sprite-based graphics
- Object-oriented programming principles

## Future Improvements

Potential enhancements for the future:
- High score system
- Sound effects and background music
- Different difficulty levels
- Additional obstacles and power-ups
- Mobile version support

## Credits

Created as a learning project to demonstrate Python game development using Pygame.
