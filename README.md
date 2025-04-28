# Flappy Bird Game

A fun and challenging Python implementation of the classic Flappy Bird game. Control a bird as it flies through a series of pipes, trying to achieve the highest score possible!

## 🎮 Game Description

Flappy Bird is a side-scrolling game where you control a bird that continuously moves forward. Your goal is to navigate the bird through gaps between pipes without touching them. The game gets progressively more challenging as your score increases.

## 🚀 Features

- Simple and addictive gameplay
- Smooth bird animation with realistic physics
- Score tracking system
- Randomly generated obstacles
- Easy-to-use controls
- Game over and restart functionality

## 🛠️ Technical Requirements

- Python 3.x
- Pygame library

## 📥 Installation

1. Make sure you have Python installed on your computer
2. Install Pygame using pip:
   ```bash
   pip install pygame
   ```
3. Download or clone this repository
4. Run the game:
   ```bash
   python flappy_bird.py
   ```

## 🎯 How to Play

### Controls:
- Press SPACE or UP ARROW to make the bird jump
- Click the mouse button to make the bird jump
- Press R or ENTER to restart after game over

### Game Rules:
1. The bird will automatically fall due to gravity
2. Press the jump button to make the bird fly upward
3. Navigate through the gaps between pipes
4. Each successful pipe pass gives you 1 point
5. The game ends if:
   - The bird hits a pipe
   - The bird hits the ground
   - The bird flies too high

## 🎨 Game Components

### The Bird
- Animated character with flapping wings
- Rotates based on its movement
- Responds to your commands for jumping

### The Pipes
- Obstacles that move from right to left
- Appear in pairs with a gap between them
- Randomly generated for endless gameplay

### Scoring System
- Score increases by 1 for each pipe passed
- Score is displayed at the top of the screen
- Try to beat your high score!

### Game Over Screen
- Appears when the bird hits an obstacle
- Shows your final score
- Includes a restart button to play again

## 📁 Project Files

- `flappy_bird.py` - Main game file
- `img/` folder contains:
  - Bird animation frames (`bird1.png`, `bird2.png`, `bird3.png`)
  - Pipe obstacle (`pipe.png`)
  - Ground texture (`ground.png`)
  - Background image (`bg.png`)
  - Restart button (`restart.png`)

## 💡 Tips for Playing

1. Time your jumps carefully
2. Don't tap too frequently
3. Try to maintain a steady rhythm
4. Focus on the next gap, not the current one
5. Practice makes perfect!

## 🔮 Future Updates

Planned improvements:
- High score system
- Sound effects and music
- Different difficulty levels
- New obstacles and challenges
- Mobile version

## 🎮 Have Fun!

Enjoy the game and challenge your friends to beat your high score! Remember, practice makes perfect in Flappy Bird.
