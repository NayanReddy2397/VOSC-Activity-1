# Tic-Tac-Toe Game

A simple and interactive two-player Tic-Tac-Toe game built using **HTML, CSS, and JavaScript**.

The project was created as part of the **VOSC Prerequisite Activity**.

## Features

- Two-player gameplay
- Player X and Player O
- Automatic turn switching
- Winner detection
- Draw detection
- Winning cells are highlighted
- New Game button
- Responsive design
- Modern dark/glass-style interface
- No external libraries or frameworks required

## Technologies Used

- **HTML5** – Used to create the structure of the game.
- **CSS3** – Used for styling, layout, animations, and responsive design.
- **JavaScript** – Used for game logic, player turns, winner detection, and restarting the game.

## Project Structure

```text
Tic-Tac-Toe/
│
├── index.html
├── style.css
├── script.js
└── README.md
```

### File Description

**index.html**

Contains the main structure of the game, including the title, player information, game board, and New Game button.

**style.css**

Controls the appearance of the game, including the background, game board, buttons, animations, colors, and responsive layout.

**script.js**

Contains the game logic. It handles player turns, cell selection, winning combinations, draw detection, and restarting the game.

## How to Run

No installation or additional software is required.

### Method 1: Directly in Browser

1. Download or clone this repository.
2. Open the project folder.
3. Double-click `index.html`.
4. The game will open in your default web browser.

### Method 2: Using VS Code

1. Open the project folder in Visual Studio Code.
2. Open `index.html`.
3. Use the **Live Server** extension to run the project.
4. The game will open in your browser.

## How to Play

1. Player X starts the game.
2. Click any empty box to place your symbol.
3. Player O gets the next turn.
4. Continue taking turns.
5. The first player to get three matching symbols in a row wins.

A winning combination can be:

```text
X | X | X
---------
O |   | O
---------
  |   |
```

Winning combinations can be horizontal, vertical, or diagonal.

If all nine boxes are filled and nobody gets three in a row, the game ends in a draw.

## Restarting the Game

Click the **New Game** button to clear the board and start a new match.

## Author

Created as a VOSC Prerequisite Activity using HTML, CSS, and JavaScript.
