# Snake Game

A simple Snake game implemented in Java using Swing.

## Introduction

This project is a classic Snake game where the player controls a snake on a grid, trying to eat apples to grow longer. The game ends if the snake collides with itself or the borders of the screen.

## Features

- Responsive arrow key controls to change the snake's direction.
- Apples randomly appear on the screen for the snake to eat.
- Score tracking to keep count of the apples eaten.
- Game over screen with the final score.

## How to Play

1. Use the arrow keys to navigate the snake.
2. Eat the red apples to grow longer.
3. Avoid colliding with the snake's own body or the screen borders.
4. Press the space bar to restart the game after the game is over.

## Installation and Execution

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/snake-game.git
   ```

2. Compile the Java files:

   ```bash
   javac game/*.java
   ```

3. Run the SnakeGame class:

   ```bash
   java game.SnakeGame
   ```

## Dependencies

- Java Swing Library

## Structure

- `GameFrame`: Initializes the game window and adds the `GamePanel`.
- `GamePanel`: Manages the game logic, drawing, and user input.
- `SnakeGame`: Main class to start the game.

## Acknowledgments

This Snake game is a simple and fun project for learning basic game development concepts using Java.


## License

This Snake game is open-source software licensed under the [MIT license](LICENSE). Feel free to use, modify, and distribute it for educational purposes.
