# Text-Based Cricket Game in Python

A lightweight, interactive command-line cricket game written in Python where a player competes against the computer.

## Features

* **Interactive Toss System:** Pick heads or tails to win the toss and choose whether to bat or bowl first.


* **Dynamic Gameplay:** Match mechanics feature a number-matching system (1–6) for both batting and bowling innings.


* **Match Constraints:** Play with a limit of 2 overs (12 balls) and 2 wickets per innings.


* **Live Score Updates:** Real-time feedback showing current runs, wickets, remaining balls, and required targets during chase sequences.



## Prerequisites

* **Python 3.x** installed on your system.



## How to Run

1. Clone the repository:
```bash
git clone https://github.com/your-username/python-cricket-game.git

```


2. Navigate to the project directory:
```bash
cd python-cricket-game

```


3. Run the Python script:
```bash
python cricket_game.py

```



## Rules of the Game

1. **The Toss:** Win the toss to decide between batting or bowling first.


2. **Batting:** Input a number from 1 to 6.


* If your choice matches the computer's choice, you lose a wicket.


* If your choice is different, your selected number is added to your total runs.




3. **Bowling:** Input a number from 1 to 6.


* If your choice matches the computer's choice, the computer loses a wicket.


* If your choice is different, the computer's selected number is added to its total runs.




4. **Winning Condition:** The player or computer with the highest total score at the end of both innings wins the match.
