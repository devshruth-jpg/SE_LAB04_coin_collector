Lab 4: VibeCoding - Coin Collector

Name: M Devashruth
SRN: PES1UG24CS251 (Section E)
Course: Software Engineering, PES University

## About
A top-down Coin Collector game built with Pygame. This lab used an LLM as a debugging and pair-programming partner to fix a bug in the provided starter code and add new features.

Original repo: https://github.com/SETAPESU26/06_coin_collector

## What was done

1. Bug fix: Coins were never removed after being touched, so the score kept increasing every frame while the player overlapped a coin. Collected coins are now removed from the game, so each coin is collected exactly once.
2. Multiple coin types: Bronze (1 point), silver (3 points) and gold (5 points), each with its own color. Bronze is the most common and gold the rarest.
3. Obstacles: Obstacles spawn inside the play area, near the coins. The player has 3 lives and loses one when touching an obstacle. A short invincibility period after each hit stops lives being lost every frame.
4. Timed round: A 30-second countdown is shown on screen. The round ends when the timer reaches zero, when lives reach zero, or when all coins are collected. A game over screen shows the final score, and pressing R resets the score, lives, timer, coins and obstacles for a new round.

## How to run

1. Install Python 3.10 or higher.
2. Go into the game folder:
   cd Lab-4/coin-collector
3. Install the dependencies:
   pip install -r requirements.txt
4. Run the game:
   python main.py

Controls:
- Arrow keys: move the player
- R: restart after the game is over

## Folder structure

Lab-4/
- coin-collector/   (updated game code)
- before.mp4        (gameplay before changes, showing the bug)
- after.mp4         (gameplay after all changes)
- chat_history.pdf  (full LLM chat history)
- chat_link.txt     (link to the shared chat)

## Chat history
https://chatgpt.com/share/6acb226d-7ab8-83ee-80ed-c49de5a83f89
