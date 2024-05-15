# Minesweeper 

## Introduction
This is a graphical implementation of the classic Minesweeper game, developed using Python and the Pygame library. The game includes both manual play and an AI agent that can make safe moves and, if necessary, random moves. 

## Requirements
- Python 3.x
- Pygame library

## Installation
1. **Clone the repository:**
   ```
   git clone https://github.com/yourusername/minesweeper.git
   ```
2. ## Navigate to the project directory:
   ```
   cd minesweeper
   ```

3. ## Install the required libraries:
  ```
   pip install -r requirements.txt
   ```

## Usage
Run the game using the following command:

```
python main.py
```

This will start the Minesweeper game and display the main window.

## Controls
* Left Click: Reveal a cell.
* Right Click: Flag or unflag a cell.
* AI Move Button: Let the AI make a move.
* Reset Button: Reset the game to its initial state.

## AI Functionality
The AI agent in the game can make safe moves based on its knowledge. If no safe moves are known, the AI can make a random move. The AI updates its knowledge with each move and flags cells that are likely to contain mines.
