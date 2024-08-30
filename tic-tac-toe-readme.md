# Tic-Tac-Toe Game

This is a command-line implementation of the classic Tic-Tac-Toe game, written in C++. The game features a player versus computer mode, where the computer uses the minimax algorithm to make optimal moves.

## Features

- Player vs Computer gameplay
- Unbeatable AI using the minimax algorithm
- Random selection of who goes first
- Option to play multiple games

## Requirements

- C++11 or later
- A C++ compiler (e.g., g++, clang++)
- Standard C++ libraries

## Compilation

To compile the game, use the following command in your terminal:

```
g++ -std=c++11 -o tictactoe main.cpp
```

Replace `main.cpp` with the actual filename if it's different.

## How to Play

1. Run the compiled executable:
   ```
   ./tictactoe
   ```

2. The game will randomly decide who goes first.

3. If it's your turn, enter a number from 1 to 9 to place your mark on the board:
   ```
   1 | 2 | 3
   ---------
   4 | 5 | 6
   ---------
   7 | 8 | 9
   ```

4. The computer will automatically make its move after yours.

5. The game continues until there's a winner or a tie.

6. After each game, you'll be asked if you want to play again.

## Game Rules

- The player uses 'X' and the computer uses 'O'.
- The first to get three of their marks in a row (vertically, horizontally, or diagonally) wins.
- If the board is full and no one has won, the game is a tie.

## Code Structure

The game is implemented using object-oriented programming principles:

- `TicTacToe` class: Encapsulates the game logic, board state, and AI.
- `main()` function: Handles the game loop and user interaction.

## Future Improvements

- Add a two-player mode
- Implement difficulty levels for the AI
- Create a graphical user interface

## Contributing

Feel free to fork this project and submit pull requests with improvements or bug fixes. For major changes, please open an issue first to discuss what you would like to change.

## License

This project is open source and available under the [MIT License](https://opensource.org/licenses/MIT).
