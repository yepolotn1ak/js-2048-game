# 2048 game

## Description
  A JavaScript implementation of the 2048 game, where players combine tiles to reach the number 2048.

  Okay, okay. Also, we have some rules:
  1) The game field is 4 x 4
  2) Each cell can be empty or contain one of the numbers: 2, 4, 8 ... 2^n
  3) The player can move cells with keyboard arrows
  4) All the numbers should be moved in the selected direction until all empty cells are filled in
    - 2 equal cells should be merged into a doubled number
    - The merged cell can’t be merged twice during one move
  5) The move is possible if at least one cell is changed after the move
  6) After move 2 or 4 appears in a random empty cell. 4 probability is 10%
  7) When 2048 value is displayed in any cell, win message should be shown.

## Technologies Used
- HTML
- CSS (SCSS)
- JavaScript

## Links
- **Preview:** [DEMO LINK](https://yepolotn1ak.github.io/js_2048_game/)
- **Mockup:** [Original 2048](https://play2048.co/)

## Launch Instructions
1. **Fork** the repo.
2. **Clone** the forked repo.
3. Run `npm install` (or `npm i`).
4. Run `npm start`.
