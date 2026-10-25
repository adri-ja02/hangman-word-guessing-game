
# Hangman Word Guessing Game

A simple console-based Hangman game developed in Python as part of my Datheon Python Programming Internship.

## Features

- Random English word selection
- Word list loaded from a text file
- Hidden word displayed using underscores
- Letter-by-letter guessing
- Six incorrect attempts allowed
- ASCII hangman drawings that update after incorrect guesses
- Duplicate guess detection
- Input validation
- Win and lose messages
- Option to play again

## Technologies Used

- Python 3
- random module
- File handling
- Sets and functions

## Requirements

- Python 3 installed
- `hangman.py`
- `google-10000-english-no-swears.txt`

## How to Run

1. Download or clone this repository.
2. Keep both files in the same folder.
3. Open a terminal in the project folder.
4. Run:

   ```bash
   python hangman.py
   ```

## How to Play

1. Run the program.
2. Guess one English letter at a time.
3. Correct guesses reveal letters in the word.
4. Avoid six incorrect guesses.
5. Guess the full word to win.

## Word List

The game uses the Google 10,000 English words list without swear words:

https://github.com/first20hours/google-10000-english

## Author

Created as a Python programming internship project.
