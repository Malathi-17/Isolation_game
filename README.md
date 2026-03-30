# AI-Powered Isolation Strategy Game

An interactive AI-driven turn-based strategy game built using Python. This project demonstrates intelligent move selection, dynamic game state management, and human vs AI gameplay through a configurable board-based environment.

## Overview

This project is based on the Isolation board game, where two players move across a grid while blocking previously occupied cells. The objective is to trap the opponent so they have no valid moves left.

The system supports both Player vs AI and Player vs Player gameplay modes. It also includes customizable board sizes, multiple chess-inspired movement pieces, and an interactive graphical interface.

## Features

* AI opponent with strategic move selection
* Turn-based interactive gameplay
* Configurable grid sizes from 5x5 to 8x8
* Multiple piece types:

  * King
  * Queen
  * Rook
  * Bishop
  * Knight
  * Pawn
* Dynamic move highlighting
* Game state tracking and validation
* Game over detection
* Visual enhancements including UI effects and particles
* Multiple gameplay modes:

  * Player vs AI
  * Player vs Player

## Objective of the Game

The goal of the game is to isolate your opponent by moving strategically across the board. Every square a player leaves becomes blocked and cannot be used again. The player who leaves the opponent with no valid moves wins the game.

## AI Concepts Used

This project demonstrates practical artificial intelligence and system design concepts such as:

* Decision-making logic
* Rule-based move generation
* State representation
* Constraint-based move evaluation
* Turn-based adversarial reasoning
* Human-AI interaction design

## Technologies Used

* Python
* Arcade / Pygame
* Object-Oriented Programming
* Basic AI logic
* Game state modeling

## How the Game Works

1. Launch the game.
2. Select a game mode:

   * Player vs AI
   * Player vs Player
3. Choose a board size or enter a custom grid size.
4. Select the movement piece type.
5. Start the match.
6. Players take turns moving across the board according to the selected piece movement rules.
7. Each previously occupied square becomes blocked after a move.
8. The game ends when one player has no valid moves left.

## Piece Movement Rules

Each player can choose one of the following movement types:

* **King** – moves one square in any direction
* **Queen** – moves any number of squares in any direction
* **Rook** – moves horizontally or vertically
* **Bishop** – moves diagonally
* **Knight** – moves in L-shaped jumps
* **Pawn** – moves one square forward depending on direction rules implemented

These movement rules influence strategy and directly affect gameplay complexity.

## Project Structure

```bash
ai_game1.py
background.png
king.png
queen.png
rook.png
bishop.png
knight.png
pawn.png
```

## Installation

Clone the repository:

```bash
git clone https://github.com/your-username/your-repository-name.git
cd your-repository-name
```

Install dependencies:

```bash
pip install pygame arcade
```

Run the project:

```bash
python ai_game1.py
```

## Future Improvements

* Improve AI using Minimax with Alpha-Beta Pruning
* Add difficulty levels
* Add sound effects and background music
* Improve animations and transitions
* Add move history and replay system
* Add score tracking
* Add timer-based gameplay
* Improve AI heuristics and board evaluation

## Learning Outcomes

Through this project, the following concepts were explored and implemented:

* AI-based decision logic
* State-space modeling
* Event-driven programming
* Interactive UI design
* Game loop architecture
* Strategy-based system behavior
* Human-AI interaction principles


## Author

Malathi,Prawin

## License

This project is created for academic purposes.
