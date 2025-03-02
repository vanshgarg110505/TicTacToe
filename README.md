# Tic-Tac-Toe Game in Java

## Overview
This is a simple command-line Tic-Tac-Toe game implemented in Java. It allows two players to take turns marking spaces on a 3x3 board until one player wins or the game ends in a draw.

## Features
- Two-player gameplay
- Input validation to prevent overwriting existing moves
- Checks for winning conditions (rows, columns, diagonals)
- Displays the game board after every move

## How to Play
1. Players take turns entering row and column indices (0-based) to place their mark ('X' or 'O').
2. The game checks for a win after every move.
3. If a player wins, the game announces the winner and ends.
4. If all spaces are filled with no winner, the game ends in a draw.

## Installation & Execution
1. Clone the repository:
   ```sh
   git clone https://github.com/yourusername/tic-tac-toe-java.git
   cd tic-tac-toe-java
2. Compile the Java program:
   ```sh
   javac Main.java
3. Run the program:
   ```sh
   java Main

## Code Structure

- `Main.java`: Contains the game logic, board initialization, player input handling, and winner checking functions.

## Example Gameplay

```
  |   |   | 
  |   |   | 
  |   |   | 
Player X enter: 0 0

X |   |   | 
  |   |   | 
  |   |   | 
Player O enter: 1 1

X |   |   | 
  | O |   | 
  |   |   | 
Player X enter: 0 1

X | X |   | 
  | O |   | 
  |   |   | 
Player O enter: 2 2

X | X |   | 
  | O |   | 
  |   | O | 
Player X enter: 0 2

Player X has won: 
X | X | X | 
  | O |   | 
  |   | O | 


