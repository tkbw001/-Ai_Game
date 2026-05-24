# Ai_Game

```md
# 🎮 Connect 4 AI Master 🤖

A fully-featured Connect 4 game built with Python and Pygame, featuring a smart AI opponent powered by the Minimax algorithm with Alpha-Beta Pruning.

## ✨ Features
* **3 Game Modes:** * 🧑‍🤝‍🧑 Human vs Human
  * 🤖 Human vs AI 
  * 👾 AI vs AI (Sit back and watch the bots battle!)
* **Smart AI Opponent:** Uses the Minimax algorithm enhanced with Alpha-Beta pruning to calculate the best possible moves and block yours.
* **Interactive GUI:** Smooth graphics and interactive mouse controls built with Pygame.
* **Customizable Difficulty:** Easily adjust the `AI_DEPTH` constant in the code to make the AI harder or easier to beat.

## 🚀 Prerequisites
Ensure you have Python 3.x installed along with the required libraries:
```bash
pip install pygame numpy

```

## 🕹️ How to Play

1. Run the game script in your terminal:
```bash
python connect4.py

```


2. Look at the console to choose your game mode (1, 2, or 3).
3. A Pygame window will open. Use your mouse to hover over the columns and click to drop your piece.
4. Connect 4 pieces of your color horizontally, vertically, or diagonally to win!

## 🧠 AI & Algorithm Details

The AI evaluates board positions using a custom heuristic scoring function. It heavily prioritizes:

* Controlling the center column.
* Building sequences of 2 or 3 pieces.
* Immediately blocking the opponent's winning moves.

By looking ahead `AI_DEPTH` moves (default is 4), the AI predicts future board states to choose the optimal drop location while pruning irrelevant branches using Alpha-Beta to save computation time.

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! Feel free to fork this repository and implement performance upgrades like Bitboards or transposition tables.

```


```
