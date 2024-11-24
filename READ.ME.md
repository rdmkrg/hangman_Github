# Hangman Game

A simple terminal-based Hangman game implemented in Python. The game challenges the player to guess a randomly chosen word by either guessing individual letters or the entire word before running out of attempts.

## Features

    - Random Word Selection: Words are selected randomly from a predefined word list.
    - User-Friendly Gameplay:
    - Players can guess single letters or the entire word.
    - Displays the current progress of the word and a hangman scaffold based on remaining attempts.
    - Replay Functionality: Allows players to replay the game after a win or loss.
    - Error Handling: Validates inputs to ensure they are appropriate guesses.

## Requirements

- Python 3.7 or later

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/rdmkrg/hangman-game.git
   cd hangman-game

2. Ensure Python is installed:
    python --version

## How to run?
1. Run the hangman.py file:
    python hangman.py

2. Follow the on-screen instructions to guess letters or words.

## Example Gameplay

    1. The game starts with the hangman scaffold and underscores representing the word:

    Let's play Hangman!
    --------
    |      |
    |
    |
    |
    |
    -
    _ _ _ _ _ _ _

    2. The player guesses letters or words, and the game responds with feedback and updates:

    Please guess a letter or word: A
    Good job, A is in the word!
    --------
    |      |
    |
    |
    |
    |
    -
    _ A _ _ _ _ _

    3. The game ends with a win or loss message:

    Congrats, you guessed the word! You win!


## Word pool (words.py)
    The words.py file contains a list of words used for the game. Example:

    word_list = [
    "python", 
    "hangman", 
    "developer", 
    "terminal", 
    "programming"
]

