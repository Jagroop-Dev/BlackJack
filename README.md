# ♠ Python Blackjack Game

[![Python](https://img.shields.io/badge/Python-3.8%2B-blue.svg)](https://www.python.org/)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
[![Platform](https://img.shields.io/badge/Platform-Cross--Platform-lightgrey.svg)](https://www.python.org/)

> CLI-based Blackjack game built with Python fundamentals and object-oriented programming.

## 🎯 Overview

This interactive command-line Blackjack game provides an authentic casino experience right in your terminal. Built using Python's core concepts including classes, inheritance, and game logic, it offers a complete implementation of the classic card game with proper blackjack rules and gameplay mechanics.

### 🎮 Why This Project?

- **Learn Python OOP**: Demonstrates classes, objects, and method interactions
- **Authentic Gameplay**: Follows standard blackjack rules and dealer behavior
- **Interactive Experience**: Real-time decision making with hit/stand options

## ✨ Features

### 🃏 **Complete Card System**
- Full 52-card deck with suits and ranks
- Proper card shuffling and dealing mechanics
- Ace value handling (11 or 1 based on hand total)
- Card display with suit symbols

### 🎲 **Authentic Blackjack Rules**
- Dealer hits on 16, stands on 17
- Natural blackjack detection (21 with 2 cards)
- Player bust and dealer bust handling
- Proper win/loss/tie conditions

### 🎮 **Interactive Gameplay**
- Multiple games per session
- Player choice system (Hit/Stand)
- Real-time hand value calculation
- Hidden dealer card until player stands

### 🖥️ **User-Friendly Interface**
- Clear terminal output with game formatting
- Intuitive command prompts
- Game-by-game progression tracking
- Final results display

## 🛠️ Technologies Used

| Category | Technologies |
|----------|-------------|
| **Language** | ![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white) |
| **Concepts** | Object-Oriented Programming, Random Module, CLI Interface |
| **Design Patterns** | Class-based architecture, Encapsulation, Method chaining |

## 🚀 Installation & Usage

### Prerequisites

- Python 3.8 or higher
- No additional dependencies required (uses only built-in modules)

### How to Run

1. **Download the game**
   ```bash
   # Save the main.py file to your desired directory
   ```

2. **Run the game**
   ```bash
   python main.py
   ```

3. **Follow the prompts**
   ```
   Enter number of games to play
   Choose Hit or Stand for each hand
   Enjoy the game!
   ```

## 💡 Gameplay

### Game Flow

1. **Setup**: Choose how many games you want to play
2. **Deal**: Each player gets 2 cards, dealer gets 2 (one hidden)
3. **Player Turn**: Hit to get more cards or Stand to keep current total
4. **Dealer Turn**: Dealer reveals hidden card and hits until 17+
5. **Results**: Compare totals to determine winner

### Commands

- **Hit**: `hit` or `h` - Draw another card
- **Stand**: `stand` or `s` - Keep current hand total

### Winning Conditions

- **Blackjack**: Natural 21 with 2 cards (Ace + 10-value card)
- **Player Wins**: Higher total than dealer without busting
- **Dealer Wins**: Higher total than player, or player busts
- **Tie**: Same total values
- **Bust**: Hand total exceeds 21

## 🏗️ Code Structure

```
main.py
├── Card Class          # Individual card representation
├── Deck Class          # 52-card deck with shuffle/deal methods
├── Hand Class          # Player/dealer hand management
└── Game Class          # Main game loop and logic
```


**Built with Python fundamentals and OOP principles**

[⬆ Back to Top](#-python-blackjack-game)

</div>
