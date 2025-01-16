# Four Board Game

## Overview
**Four** is a two-player strategy board game that enhances the classic Connect Four concept by adding a three-dimensional twist. Played on a 4x4x4 grid, it challenges players to think strategically in three dimensions to align four of their pieces in a row.

---

## Game Mechanics

### Objective
The primary goal is to be the first player to align four of your pieces in a row. This can be achieved:
- Horizontally
- Vertically
- Diagonally
- Across different layers of the 3D grid

### How to Play
1. **Turn-Based Gameplay**:
   - Players take turns placing their pieces (red or yellow) on the grid.
   - Pieces "fall" to the lowest available position in the chosen column, mimicking gravity.
2. **Winning Conditions**:
   - Align four pieces in any direction (horizontal, vertical, diagonal, or multi-layered diagonal).
3. **Draw Condition**:
   - If all spaces are filled and no winning combination is achieved, the game ends in a draw.

---

## Screenshots
### Main Menu
![Main Menu](![Screenshot 2025-01-16 131902](https://github.com/user-attachments/assets/ca87b317-f062-4864-9e7c-4a2aad2b0914)
)
- Options to start a new game, load a saved game, view rules, or exit.

### Gameplay - Initial Moves
![Gameplay - Early Moves]()
- Players begin by placing their pieces on the 9x9 grid.

### Mid-Game Strategy
![Gameplay - Mid-Game](![Screenshot 2025-01-16 132104](https://github.com/user-attachments/assets/6f3aab80-dd78-4f43-91fc-d85f05368536)
)
- The board begins to fill as players strategize their moves.

### Endgame and Victory
![Gameplay - Endgame](sandbox:/mnt/data/game_screenshots/screenshot_450.png)
- A winning move showcases the alignment of four pieces.

---

## Features

### User Interface
- **Main Menu**: Intuitive design for easy navigation.
- **Game Board**: Clear visual representation of the 4x4 grid.
- **Player Turn Indicator**: Highlights the current player.
- **Move Counter**: Tracks the number of moves made.

### Game Functionality
1. **Gravity Simulation**:
   - Pieces fall to the lowest available position in the selected column.
2. **Winning Logic**:
   - Real-time detection of winning combinations.
3. **Save and Load**:
   - Save game progress and resume later using Java's serialization.
4. **Multiplayer Support**:
   - Local multiplayer for two players on the same device.

---

## Technical Implementation
- **Programming Language**: Java
- **GUI Framework**: Java Swing
- **Data Structures**: 3D array for the game board.
- **Design Pattern**: MVC (Model-View-Controller) for a modular and maintainable architecture.

---

## Future Enhancements
- Network multiplayer functionality.
- Advanced AI opponent with adjustable difficulty.
- 3D graphical representation of the game board.
- Undo/Redo functionality for moves.

---

## Development Details
- **Development Period**: October 2024 - November 2024
- **Team Size**: 3 Programmers
- **Role**: Developer and UI Designer

### Key Contributions
- Designed and implemented a user-friendly UI.
- Developed save/load functionality.
- Ensured smooth gameplay mechanics and real-time win detection.

---

## Media
For a demonstration of the game, check out the video below:

https://github.com/user-attachments/assets/f9125c5d-cabe-4b49-9a16-69b82121275b

