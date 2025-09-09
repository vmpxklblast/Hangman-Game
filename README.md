# Hangman Game

A simple command-line Hangman game written in Python.

## How to Play

1. Run the game:
    ```bash
    python hangman.py
    ```
2. The game will select a random word and display blanks for each letter.
3. You have 6 incorrect guesses. Each time you guess a letter not in the word, you lose an attempt.
4. Guess letters one at a time. Already guessed letters will be notified.
5. Win by guessing all letters before running out of attempts!

## Features

- Random word selection from a predefined list.
- Tracks guessed letters and remaining attempts.
- User-friendly prompts and game over messages.

## Requirements

- Python 3.x

## Customization

- You can add more words to the list in `choose_word()` for variety.

## Example Game

```
Welcome to Hangman!
The word has 8 letters.

_ _ _ _ _ _ _ _
Guess a letter: a
Wrong guess! You have 5 attempts left.

_ _ _ _ _ _ _ _
Guess a letter: p
Good guess! 'p' is in the word.
...
```

Enjoy playing Hangman!
