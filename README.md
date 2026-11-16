# ❌⭕ Tic-Tac-Toe | JavaScript Game

An interactive, two-player Tic-Tac-Toe game project focused on **JavaScript, DOM manipulation, and Object-Oriented Programming (OOP)**.

Originally created as a coding challenge through **Resilient Coders**, this project explores game logic, player interaction, and organizing JavaScript code using object-oriented design principles.

Live Link: https://morning-challenge-tic-tac-toe.onrender.com

## 🎯 Project Overview

<img width="944" height="502" alt="image" src="https://github.com/user-attachments/assets/8aaa8cea-637e-48a3-a959-5e3d987e367e" />

The goal is to build a browser-based Tic-Tac-Toe game where two players take turns placing X's and O's on a 3×3 grid.

The application should track player turns, evaluate winning combinations, and display the winner directly on the webpage.

A central objective is to use **Object-Oriented Programming** to organize game functionality into reusable, maintainable components.

## ✨Features

- **Two-player gameplay:** Players alternate between X and O.
- **Interactive game board:** Click an available square to place a mark.
- **Turn management:** Track which player moves next.
- **Win detection:** Identify three matching symbols in a row, column, or diagonal.
- **Winner announcement:** Display a winning message dynamically in the DOM.
- **Game-state management:** Prevent invalid moves and stop play after a winner is determined.
- **Object-oriented design:** Organize players, board state, and game rules into reusable JavaScript structures.

## 🛠️ Technologies

| Technology | Purpose |
|---|---|
| HTML5 | Structure the game board |
| CSS3 | Style the interface |
| JavaScript | Handle game logic and player interaction |
| Git & GitHub | Version control and collaboration |

## 🎮 How to Play

1. Two players participate, one using **X** and the other using **O**.
2. Player X selects an empty square to begin.
3. Player O selects another empty square.
4. Players continue taking turns.
5. The first player to place three matching symbols horizontally, vertically, or diagonally wins.
6. The game displays the winner on the webpage.
7. If all nine squares are filled without a winner, the game ends in a draw.

## 🧠 Game Logic

The intended game logic involves:

### Board Management

Represent the game board using nine positions arranged in a 3×3 grid.

### Player Turns

Track the current player and alternate between X and O after each valid move.

### Winning Conditions

Evaluate eight possible winning combinations:

- Three horizontal rows
- Three vertical columns
- Two diagonals

### Game Completion

After each move, check whether a player has won or whether the board is full.

Once the game ends, display the result and prevent additional moves.

 building interactive games and practicing object-oriented design.*
