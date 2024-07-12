# Snake Game

A simple implementation of the classic Snake game using Python's `tkinter` library.

## Game Description

In this game, you control a snake to eat food and grow longer. The game ends if the snake collides with the walls or with itself. The objective is to eat as much food as possible and achieve the highest score.

## Features

- Classic Snake gameplay
- Score tracking
- Game Over message
- Playable in a resizable window
- Smooth animations with a frame rate of 10 frames per second


## How to Play

- **Start the game**: The game window will open automatically when you run the script.
- **Control the snake**: Use the arrow keys on your keyboard to move the snake:
  - Up: `↑`
  - Down: `↓`
  - Left: `←`
  - Right: `→`
- **Score points**: Guide the snake to the red food. Each time the snake eats the food, it grows longer, and you score a point.
- **Game over**: The game ends if the snake collides with the window boundaries or its own body.

## Code Overview

### Main Components

1. **Tile Class**:
    - Represents each tile on the game grid.
    - Stores the `x` and `y` coordinates of the tile.

2. **Game Initialization**:
    - Sets up the game window and canvas.
    - Initializes the snake's head, food, snake body, and game variables.

3. **Game Loop Functions**:
    - `change_direction(e)`: Handles the change in snake's direction based on key presses.
    - `move()`: Updates the snake's position and handles collisions.
    - `draw()`: Draws the snake and food on the canvas and updates the game state.

### Game Variables

- `ROWS`, `COLS`, `TILE_SIZE`: Grid dimensions and tile size.
- `WINDOW_WIDTH`, `WINDOW_HEIGHT`: Window dimensions.
- `snake`: The head of the snake.
- `food`: The food tile.
- `velocityX`, `velocityY`: Snake's movement velocity.
- `snake_body`: List of tiles representing the snake's body.
- `game_over`: Game over state flag.
- `score`: Player's score.

## Future Enhancements

- Add sound effects for eating food and game over.
- Implement levels with increasing difficulty.
- Add a main menu and pause functionality.
- Improve graphics with custom sprites.

## License

This project is open source and available under the [MIT License](LICENSE).

## Credits

- Developed by [Akshay](https://github.com/Akshay-coded).
- Inspired by the classic Snake game.
