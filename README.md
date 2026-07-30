# 🃏 Python Blackjack

A simple command-line Blackjack game written in Python. The game allows a player to compete against a computer dealer using a deck of numbered cards. The objective is to get as close to 21 as possible without going over.

## Features

- Random card drawing from a deck
- Interactive player turn (Hit or Pass)
- Computer dealer that draws until reaching at least 17
- Win/loss determination based on Blackjack rules
- Input validation for player choices
- Easy-to-read terminal interface

## How It Works

1. The player is dealt two random cards.
2. The player chooses to:
   - **Hit** – Draw another card.
   - **Pass** – End their turn.
3. The computer takes its turn and continues drawing until its total is at least 17.
4. The game compares both totals to determine the winner.

## Technologies Used

- Python 3
- `random` module

## Running the Project

1. Clone this repository:

```bash
git clone https://github.com/YOUR_USERNAME/python-blackjack.git
```

2. Navigate to the project folder:

```bash
cd python-blackjack
```

3. Run the program:

```bash
python blackjack.py
```

## Example Gameplay

```
Welcome to Blackjack!

Your first two cards are: 7 9
Player Total: 16

Would you like to Hit or Pass?
> Hit

Card value: 3
Total = 19

------Computer's Turn------

Computer drew: 8
Computer Total: 18

Congratulations, You win!!
```

## Project Structure

```
.
├── blackjack.py
├── README.md
└── Blackjack_python.pdf
```

## Future Improvements

- Add face cards (Jack, Queen, King)
- Implement Ace as either 1 or 11
- Multiple rounds with score tracking
- Betting system
- Better card display using Unicode suits
- Graphical user interface (Tkinter or Pygame)
- Improved object-oriented design using classes

## What I Learned

While building this project, I practiced:

- Functions and modular programming
- Variables and global state
- Lists and list manipulation
- Random number generation
- Loops and conditional logic
- User input validation
- Building an interactive terminal application

## Author

**Neil Kandekar**

Senior student interested in Cybersecurity and Software Development.

---

*This project was created as a Python programming exercise to demonstrate problem-solving, game logic, and fundamental programming concepts.*
