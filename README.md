# Snake Game

This is a Snake Game built using HTML5 Canvas and JavaScript, featuring simple game logic and interactive functionality.

## Features

- **Game Screen**: The game screen is drawn using Canvas, including the snake, food, and background.
- **Keyboard Controls**: Use arrow keys to control the snake's movement.
- **Collision Detection**:
  - Colliding with walls ends the game.
  - Colliding with itself ends the game.
  - Eating food extends the snake and increases the score.
- **Score Display**: The current score is displayed at the top-left corner of the game screen.
- **Refresh Button**: Click the button to restart the game.

## Game Screen

The game screen includes the following elements:

- **Snake**: Composed of multiple rectangles with random colors.
- **Food**: A red rectangle randomly generated at positions not overlapping with the snake.
- **Background**: A black background for a clear visual experience.

## How to Run

1. Ensure you have a modern browser installed (e.g., Chrome, Firefox).
2. Download or clone the project to your local machine.
3. Open the `FullSnake.html` file in your browser to run the game.

Alternatively, you can play the game online by clicking the link below:

[Start Playing](https://opming7788.github.io/Greedy_Snake/FullSnake.html)

## Controls

- Use the arrow keys to control the snake's movement:
  - Up: `↑`
  - Down: `↓`
  - Left: `←`
  - Right: `→`
- Click the "Refresh" button to restart the game.

## Game Logic

1. **Initialization**:
   - Create the snake, food, and background.
   - Set the initial score and speed.
2. **Game Loop**:
   - Update the snake's movement direction based on arrow key input.
   - Move the snake and check for collisions:
     - Colliding with walls or itself ends the game.
     - Eating food extends the snake and increases the score.
   - Update the screen and continue the game loop.
3. **Game Over**:
   - Display "GG" and stop the game.

## File Structure

```
/SnakeGame
├── FullSnake.html  # Main game file
├── README.md       # Project description file
```

## Contribution

Feel free to submit issues or suggestions, or contribute code improvements via Pull Requests.

## License

This project is licensed under the MIT License. See [LICENSE](https://opensource.org/licenses/MIT) for details.
