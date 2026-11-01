# Hangman Game

A classic Hangman word-guessing game written in Python that you play in the terminal. The computer picks a random word and you guess it one letter at a time.

---

## How to play

- A random word is chosen from the list: `python`, `apple`, `banana`, `computer`, `school`
- The word is shown as blanks (`_ _ _ _ _ _`)
- Enter one letter at a time
  - Correct letter: it appears in the word
  - Wrong letter: you lose one attempt
- You have **6 wrong guesses**. Guess the whole word before they run out to win!

## Features

- Random word selection
- Shows your progress after every guess
- Remembers guessed letters and warns you if you repeat a letter
- Remaining attempts counter
- Win and game-over messages

## Tech and concepts

Python 3 | `random` module | lists | strings | `while` loop with `else` | user input

## Project structure

```
CodeAlphs_HangmanGame/
├── HangmanGame.py   # Game program
└── README.md
```

## How to run

1. Install [Python 3](https://www.python.org/downloads/)
2. Clone the repository and run:
   ```bash
   git clone https://github.com/vamsidhar-reddy-81/CodeAlphs_HangmanGame.git
   cd CodeAlphs_HangmanGame
   python HangmanGame.py
   ```

## Sample game

```
Welcome to Hangman!

Word: _ _ _ _ _ _
Enter a letter: p
Correct!

Word: p _ _ _ _ _
Enter a letter: z
Wrong guess!
Remaining attempts: 5

Word: p _ _ _ _ _
Enter a letter: y
Correct!

...

Word: p y t h o n
🎉 Congratulations! You guessed the word: python
```

## Ideas to improve

- Draw the hangman figure in text for each wrong guess
- Load words from a file and add difficulty levels
- Add a "play again" option

## Author

**Vamsidhar Reddy**
GitHub: [vamsidhar-reddy-81](https://github.com/vamsidhar-reddy-81) | LinkedIn: [Vamsidhar Reddy](https://www.linkedin.com/in/morreddy-gari-vamsidharreddy-4b0640378/)
