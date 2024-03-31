# Snake Game

This is a classic Snake Game implemented in C++ using console-based input and output. The game allows players to control a snake, represented by the character 'O', to eat fruits ('F') and grow longer. The objective is to grow the snake as long as possible without colliding with the walls or itself.

## Features

- Classic snake gameplay.
- Simple and intuitive controls using the keyboard: 'a' (left), 'd' (right), 'w' (up), 's' (down), and 'x' (exit).
- Random generation of fruits.
- Score tracking.

## How It Works

- **Setup:** The game initializes by setting up the initial position of the snake, fruit, and score.
- **Draw:** The game renders the game board, snake, fruit, and score on the console.
- **Input:** It captures user input using `_kbhit()` and `_getch()` functions to change the direction of the snake or exit the game.
- **Logic:** The game calculates the movement of the snake based on the user input and checks for collisions with walls, the snake itself, or the fruit.
- **Game Over:** The game ends when the snake collides with a wall or itself, and the final score is displayed.

## How to Use

1. **Compile:** Compile the source code using a C++ compiler. For example:

   ```sh
   g++ main.cpp -o main.exe
   ```

2. **Run:** Execute the compiled binary file:

   ```sh
   ./main.exe
   ```

3. **Play:** Control the snake using the keys 'a' (left), 'd' (right), 'w' (up), 's' (down), and 'x' (exit).

## Demo

Here is a short video demonstrating the gameplay.

https://github.com/AnushkaKohli/Snake-Game-in-C-/assets/102284552/085ca0ae-e161-4784-a335-9fc3ed8ab000


## Requirements

- C++ compiler
- Windows OS (for `conio.h` and `windows.h`)

## Notes

- The game may not work properly on non-Windows systems due to the use of Windows-specific functions for console input/output.
