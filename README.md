# 2048 Game Implementation

### Overview

This project is an implementation of the popular 2048 game. The game logic is developed using JavaScript, and the user interface is built with HTML and CSS. Players can interact with the game using keyboard arrow keys to combine tiles and reach the 2048 tile.

[DEMO LINK](https://mariasnegireva.github.io/2048_game/)

### Project Structure

The project consists of the following key components:

- HTML and CSS: Pre-written templates for the game interface.
- JavaScript Game Logic: Implemented in the src/modules/Game.class.js file.
- Main Script: Integrates the game logic with the UI, found in the main.js script.

### Game Features

1. Game Board: A 4x4 grid where each cell can contain numbers like 2, 4, 8, ... 2^n.
2. Tile Movement: Players can use arrow keys to move tiles in four directions.
3. Tile Merging: When two tiles with the same number collide, they merge into a tile with the doubled number.
4. Random Tile Generation: After each move, a new tile (2 or 4) appears in a random empty cell.
5. Win Condition: The game displays a win message when a tile with 2048 appears.
6. Game Over Condition: The game displays a game-over message when no more moves are available.
7. Score Tracking: The score increases by the sum of all merged tiles during each move.
8. Start/Restart Button: A button that starts the game or restarts it after the first move.
9. Dynamic UI Updates: The game board updates in real-time based on the player’s actions.

### Key Classes and Methods

- Game Class: Located in src/modules/Game.class.js. Key methods include:

- constructor(initialState): Initializes the game with an optional initial state.
- getState(): Returns the current state of the game board.
- getScore(): Returns the current score.
- getStatus(): Returns the current status (e.g., ongoing, win, game over).
- moveLeft(), moveRight(), moveUp(), moveDown(): Methods to move tiles in respective directions.
- start(): Starts the game.
- restart(): Restarts the game.

### Usage Instructions

- Setup: Ensure all project files are in the correct directories.
- Start Game: Open index.html in a web browser to view the game interface.
- Play Game: Use the arrow keys to move tiles and try to reach the 2048 tile.
- Restart Game: Click the "Restart" button to reset the game at any time.

#### Run Locally

Clone the project

```bash
  git clone
```

Go to the project directory

```bash
  cd my-project
```

Install dependencies

```bash
  npm install
```

Start the development server with the following command

```bash
  npm start
```
