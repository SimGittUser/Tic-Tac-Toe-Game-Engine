# Tic-Tac-Toe (PyQt5)

A modern desktop Tic-Tac-Toe application built with Python and PyQt5.

This project includes:
- Play vs Perfect Engine (Minimax with Alpha-Beta pruning)
- Play vs Player (1v1)
- Analyse Position mode with best-move highlighting

## Features

- Clean and responsive PyQt5 GUI
- Perfect-play AI engine using Minimax + Alpha-Beta pruning
- Separate game modes for AI and local multiplayer
- Position analysis with board evaluation and suggested move

## Tech Stack

- Python 3.8+
- PyQt5

## Required Libraries

Only one external library is required:

- PyQt5

Standard library modules used (no install needed):
- sys
- typing

## Installation

1. Clone this repository:

```bash
git clone https://github.com/SimGittUser/Tic-Tac-Toe-Game-Engine.git
cd Tic-Tac-Toe
```

2. (Optional but recommended) Create and activate a virtual environment:

```bash
python -m venv .venv
source .venv/bin/activate
```

3. Install dependencies:

```bash
pip install PyQt5
```

## Run the Application

```bash
python tic_tac_toe.py
```

## How the AI Works

The engine uses:
- Minimax to evaluate all possible outcomes
- Alpha-Beta pruning to reduce unnecessary search branches

Because Tic-Tac-Toe has a small state space, this results in perfect play.

## Notes

- In vs Engine mode, the engine plays as O.
- In Analyse Position mode, you can manually place X/O pieces and evaluate the board.
