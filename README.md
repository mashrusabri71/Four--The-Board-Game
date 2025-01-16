# Four Board Game

## Overview
**Four** is a two-player strategy board game similar to Connect Four, but with added complexity and strategic depth. The game is played on a 4x4x4 three-dimensional grid, where players aim to align four of their pieces in a row in any direction (horizontal, vertical, or diagonal).

---

## Game Rules
1. **Turn-Based Gameplay**: Players take turns placing their pieces (typically red and yellow) on the 4x4 grid.
2. **Gravity Effect**: Pieces "fall" to the lowest available space in the chosen column, as if affected by gravity.
3. **Winning Conditions**: The first player to align four of their pieces in a row (horizontally, vertically, or diagonally) wins the game.
4. **Draw Condition**: If all spaces are filled and no player has won, the game is declared a draw.

---

## Implementation Details

### User Interface
- **Main Menu**: Designed using Java Swing, offering options to:
  - Start a new game
  - Load a saved game
  - View game rules
  - Exit the game
- **Game Board**: A 4x4 grid represented visually, with a clear distinction between empty spaces and player pieces.
- **Player Turn Indicator**: Displays which player's turn it is currently.
- **Move Counter**: Tracks and displays the total number of moves made during the game.

### Game Functionality
1. **Game Logic**:
   - Turn-based gameplay implemented using Java.
   - Methods created to check for winning conditions after each move.
   - Logic developed to handle the "gravity" effect for piece placement.
2. **Save/Load Feature**:
   - Game state, including board configuration and current player turn, is saved using Java's serialization.
   - Implemented a load function to restore saved games.
3. **Multiplayer Support**:
   - Local multiplayer functionality, allowing two players to take turns on the same device.

---

## Technical Implementation
- **Programming Language**: Java
- **GUI Framework**: Java Swing
- **Data Structures**: 3D array to represent the game board
- **Design Pattern**: MVC (Model-View-Controller) to separate game logic from UI

---

## Future Enhancements
- Add network multiplayer support.
- Implement advanced AI with multiple difficulty levels.
- Introduce a 3D graphical representation of the game board.
- Add undo/redo functionality for moves.

---

## Project Details
- **Development Period**: October 2024 - November 2024
- **Team Size**: 3 Programmers
- **Role**: Developer and UI Designer

### Key Achievements
- Developed a multiplayer board game using Java and the Swing library.
- Designed user-friendly and visually clear UI prototypes for the main menu and gameplay display.
- Implemented load/save functionality, enhancing player convenience and demonstrating proficiency in object-oriented programming concepts.

---

## Media
For a visual demonstration of the game, check out the video below 

https://github.com/user-attachments/assets/f9125c5d-cabe-4b49-9a16-69b82121275b

