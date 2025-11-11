# 📘 Assignment: Hangman Game Challenge

## 🎯 Objective

Build a text-based Hangman game in Python to practice string manipulation, loops, conditionals, and user input handling. The program should be playable in the terminal and provide a clear, user-friendly experience.

## 📝 Tasks

### 🛠️ Build the Hangman Game

#### Description
Implement the core Hangman game: randomly choose a word from a predefined list, accept single-letter guesses from the player, reveal correct letters in place, track incorrect guesses, and end the game with a win or loss message.

#### Requirements
Completed program should:
- Randomly select a word from a hard-coded list of at least 10 words.
- Display the current word progress using underscores for unknown letters (e.g., _ a _ _ m a n).
- Accept only single-letter alphabetic input and ignore/handle repeated guesses.
- Track and display the number of incorrect attempts remaining (minimum 6 attempts).
- End with a clear win message when the word is fully revealed or a lose message showing the correct word when attempts run out.
- Be runnable from the command line (e.g., python3 hangman.py).

Example session:
```text
Welcome to Hangman!
Word: _ _ _ _ _ _
Guesses remaining: 6
Guess a letter: a
Good guess! Word: _ a _ _ _ _
Guesses remaining: 6
Guess a letter: z
Sorry, 'z' is not in the word.
Guesses remaining: 5
...
```

### 🛠️ Optional: Enhance the Game

#### Description
Add polish and extra features to make the game more robust and engaging.

#### Requirements
If implemented, optional features should:
- Add input validation and friendly prompts for invalid input.
- Support a scoreboard or save the player's best score (e.g., fewest wrong guesses) in a local file.
- Allow the player to choose difficulty levels that affect word length or number of attempts.
- Display a simple ASCII-art hangman that progresses with each incorrect guess (must not break core gameplay).
