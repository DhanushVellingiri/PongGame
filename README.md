# Breakout Game

A simple Breakout game implemented in Python using the Pygame library.

## Features
- Player-controlled paddle to bounce the ball.
- Bricks that disappear when hit.
- Ball movement with collision detection.
- Simple game loop with a fixed frame rate.

## Requirements
- Python 3.x
- Pygame library

## Installation
1. Ensure you have Python installed. You can download it from [python.org](https://www.python.org/).
2. Install Pygame using pip:
   ```sh
   pip install pygame
   ```

## How to Play
1. Run the game script:
   ```sh
   python breakout.py
   ```
2. Use the **Left Arrow** and **Right Arrow** keys to move the paddle.
3. Bounce the ball off the paddle to break all the bricks.
4. If the ball falls below the paddle, the game will end.

## Game Controls
- **Left Arrow Key (←)**: Move paddle left
- **Right Arrow Key (→)**: Move paddle right
- **Escape (Esc)**: Close the game window

## Code Structure
- `main()`: The main game loop handling events, movement, and rendering.
- `draw_objects()`: Handles rendering of the game objects (ball, paddle, bricks).
- Collision detection for paddle and bricks is implemented within the game loop.

## Future Improvements
- Add multiple levels with increasing difficulty.
- Implement a scoring system.
- Add sound effects and animations.
- Improve paddle and ball physics.

## License
This project is open-source and available under the MIT License.

