# Blackjack Game - Milestone Project 2

## Project Overview

This repository contains the code for a Python-based implementation of the classic Blackjack game. It was developed as part of a milestone project that walks through a complete solution, focusing on object-oriented programming (OOP) concepts. The game allows players to bet chips, play hands against the dealer, and continue playing multiple rounds while tracking their chips.

## Features

- **Deck of 52 Cards**: The game simulates a standard deck of cards with four suits and 13 ranks.
- **Player Betting System**: Players place bets and cannot exceed their available chips.
- **Gameplay Mechanics**:
  - Dealer and Player are each dealt two cards.
  - The Player can choose to "Hit" or "Stand."
  - The Dealer plays automatically, hitting until reaching a minimum hand value of 17.
  - Cards are ranked with Aces able to be worth either 1 or 11, depending on the hand.
- **Winner Determination**: After both hands are completed, the game compares hands and adjusts chips based on the result.
- **Replay Option**: Players can play multiple rounds with their chip balance carried over.

## How to Run the Game

1. **Clone the Repository**:
    ```bash
    git clone https://github.com/yourusername/blackjack-game-project.git
    ```

2. **Navigate to the Project Directory**:
    ```bash
    cd blackjack-game-project
    ```

3. **Run the Python File**:
    ```bash
    python blackjack.py
    ```

## Game Rules

- **Blackjack**: The goal is to have a hand value as close to 21 as possible without going over.
- **Card Values**:
  - Numbered cards (2-10) are worth their face value.
  - Jacks, Queens, and Kings are each worth 10 points.
  - Aces are worth 1 or 11 points, depending on which value keeps the hand closer to 21 without busting.
- **Betting**: Players bet an amount of chips and must ensure the bet doesn't exceed their available chips.
- **Hitting and Standing**:
  - Players can "Hit" to draw another card or "Stand" to stop drawing.
  - The Dealer automatically "Hits" until their hand value reaches 17 or more.
  
## Project Structure

- **blackjack.py**: Main Python file containing the game logic.
- **Classes**: The game uses OOP principles with the following classes:
  - `Card`: Represents a single card with a suit and rank.
  - `Deck`: Manages the deck of 52 cards, including shuffling and dealing.
  - `Hand`: Represents a player’s hand, tracking card values.
  - `Chips`: Manages the Player’s available chips and bets.

## Requirements

- **Python 3.x**: Ensure Python is installed on your system. You can download it [here](https://www.python.org/downloads/).

