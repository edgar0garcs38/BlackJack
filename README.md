# BlackJack (Python CLI)

A command-line BlackJack game written in object-oriented Python.

## Features
- Play several rounds in a row and choose how many games to play
- Full 52-card deck with shuffling and dealing
- Correct hand scoring, with aces counted as 1 or 11
- Detects BlackJack, busts and ties
- Dealer's hole card stays hidden until the end of the round
- Hit / Stand input with validation (`H` / `S` shortcuts)

## Design
| Class | Responsibility |
|---|---|
| `Card` | Suit and rank |
| `Deck` | Builds, shuffles and deals cards |
| `Hand` | Holds cards, calculates value, displays the hand |
| `Game` | Game loop, player decisions, dealer logic, winner check |

## Run it
```bash
python main.py
```
No dependencies, just Python 3.
