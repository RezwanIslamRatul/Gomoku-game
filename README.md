# Gomoku Game

A web-based implementation of the classic Gomoku (Five in a Row) game for two players.

## Description

Gomoku is a traditional board game where two players take turns placing pieces on a 10x10 grid. The goal is to get five pieces in a row - horizontally, vertically, or diagonally.

## Features

- 10x10 game board
- Two-player gameplay (User vs Friend)
- Score tracking system
- Win detection in all directions
- Visual highlighting of winning moves
- Interactive game instructions
- Responsive restart functionality

## Tech Stack

- HTML5
- CSS3
- JavaScript
- jQuery 3.5.1

## How to Play

1. The game starts with the User's turn
2. Players alternate turns placing their pieces on empty cells
3. First player to get 5 pieces in a row (horizontal, vertical, or diagonal) wins
4. Click "Next" to start a new game or "Restart" to reset the current game

## Score System

- Tracks individual scores for both players
- Displays total games played
- Shows score ratio for each player

## Project Structure

```
gomoku/
├── js/
│   ├── jquery.js
│   └── script.js
└── [other project files]
```

## Development

This project uses vanilla JavaScript with jQuery for DOM manipulation and event handling. The game state is managed through a 2D array, with:
- `-1` representing User's moves
- `1` representing Friend's moves
- `0` representing empty cells

## Game Logic

- Win detection checks all four directions:
  - Horizontal (→)
  - Vertical (↓)
  - Diagonal (↘)
  - Diagonal (↙)
- Victory is achieved when exactly 5 pieces are aligned
- Winning combination is highlighted on the board

## License

This project uses jQuery which is licensed under the MIT License.
