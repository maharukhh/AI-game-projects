# Tic-Tac-Toe Game (Human vs AI)

A simple Python-based Tic-Tac-Toe game where a human player plays against a basic AI that makes random moves.

## About This Project

This project is a console-based Tic-Tac-Toe game built using Python. It demonstrates basic game logic, turn-based gameplay, and simple AI behavior using random move selection.

## Features

* Human vs AI gameplay
* Interactive console interface
* Automatic win detection
* Draw detection
* Simple AI using random moves

## Technologies Used

* Python
* Random Module

## Game Rules

```text
1 | 2 | 3
--+---+--
4 | 5 | 6
--+---+--
7 | 8 | 9
```

Enter a number (1-9) to place your move.

## Project Structure

```text
tic-tac-toe-ai/
│
├── main.py              # Source Code
├── README.md            # Documentation
└── output/              # Game Output Screenshots

```

## Output

The game runs in the terminal and shows the board after every move.

Example outputs are stored in the `output/` folder.

## How to Run

```bash
python main.py
```

## Example Gameplay

```text
Choose position (1-9): 5
AI is making a move...
Current Board:
X | O |  
--+---+--
  | X |  
--+---+--
  |   | O

You win!
```

## How It Works

* Board is stored as a list of 9 elements
* Human player uses "X"
* AI uses "O"
* AI selects a random empty position
* Game checks win/draw after every move

## Limitations

* AI is random (not intelligent)
* No Minimax algorithm used
* No difficulty levels
* No graphical interface

## Future Improvements

* Implement Minimax algorithm for smart AI
* Add difficulty levels (Easy, Medium, Hard)
* Create GUI using Pygame
* Add score tracking system
* Improve AI decision making

## Author

Mahrukh

Robotics & Intelligent Systems Student passionate about Artificial Intelligence, Machine Learning, and Game Development.
