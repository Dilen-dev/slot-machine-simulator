# 🎰 Slot Machine Game

A terminal-based slot machine game written in Python. This game allows players to deposit money, place bets across multiple lines, and spin a 3x3 slot machine to try their luck!

## 🕹️ How It Works

- The player starts by depositing money.
- They choose how many lines to bet on (1 to 3).
- Then they place a bet per line (with limits).
- A 3x3 slot machine spin is generated using weighted symbols.
- The player wins if all symbols match in a horizontal line they bet on.
- Winnings depend on the symbol's value and the amount bet.
- The game continues until the player quits or runs out of money.

## 🧩 Game Features

- Symbol probabilities and payouts:
  - A (rare, high payout)
  - B
  - C
  - D (common, low payout)
- Input validation for:
  - Deposit amount
  - Number of lines to bet on
  - Bet per line
- Balances updated after each round.
- Winning lines and amounts are clearly displayed.

## 💰 Betting Rules

- **Minimum Bet per Line**: $1  
- **Maximum Bet per Line**: $100  
- **Maximum Lines to Bet On**: 3  
- **Symbol Values**:  
  - A = $5  
  - B = $4  
  - C = $3  
  - D = $2

## 🛠 Requirements

- Python 3.x

## 🚀 How to Run

1. Make sure Python is installed on your system.
2. Download or clone this repository.
3. Open a terminal and run the script:

```bash
python Slot_machine.py
