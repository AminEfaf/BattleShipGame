# Battleship Game

## Project Overview

Battleship is a strategy game where players engage in a naval battle on an nxn game board. The size of the board (n) is an odd number between 5 and 20, ensuring a dynamic and challenging experience. Players deploy ships, take turns firing at each other’s fleets, and strive to outmaneuver their opponent to achieve victory.

---

## Features

1. **Customizable Board Size**: The game board can be configured with dimensions between 5x5 and 20x20.
2. **Strategic Ship Placement**: Players deploy their fleet within their designated side of the board.
3. **Turn-Based Gameplay**: Players alternate turns, selecting coordinates to fire at the opponent’s fleet.
4. **Randomized Enemy Shots**: The AI-controlled enemy fires at random coordinates, adding unpredictability.
5. **Score Calculation**: A comprehensive scoring system evaluates player performance.

---

## How to Play

1. **Setup:**
   - Choose the board size (n), which must be an odd number between 5 and 20.
   - Deploy your ships strategically within your side of the board, avoiding the border and opponent’s side.

2. **Gameplay:**
   - On each turn, select a coordinate (x, y) to fire at the opponent’s side.
   - The enemy AI will take its turn, firing random shots at your fleet.
   - Receive feedback on hits (`1`) and misses (`0`) for both players.

3. **Scoring System:**
   - Your score is calculated using the formula:
     
     `c + ( n / (i+1) ) + l`
     
     Where:
     - `c` = Number of correct shots.
     - `n` = Size of the game board.
     - `i` = Number of misfires.
     - `l` = Number of your remaining ships.

4. **End of Game:**
   - The game ends when all ships of either player are destroyed.
   - Victory is achieved by sinking the opponent’s fleet.
   - The final result and score are displayed at the end of the game.

---

## Feedback

We’d love to hear your thoughts and suggestions! Feel free to reach out or open an issue in this repository.
