```markdown
# 📘 Assignment: Hangman Game

## 🎯 Objective

Build a playable Hangman word-guessing game to practice string manipulation, loops, conditionals, and user input/output in Python. Students will implement core game logic and optionally add enhancements.

## 📝 Tasks

### 🛠️ Task 1 — Core Game

#### Description
Implement the core Hangman game loop that lets a player guess letters to reveal a hidden word while tracking remaining attempts.

#### Requirements
Completed program should:

- Randomly select a secret word from a predefined list (or `words.txt` if available).
- Prompt the player for single-letter guesses and validate input.
- Display current progress using underscores and revealed letters (e.g. `_ a _ _ m a n`).
- Track and display letters already guessed and remaining incorrect attempts.
- End the game with a clear win or lose message and reveal the word.

### 🛠️ Task 2 — Enhancements (Optional)

#### Description
Add extra features to improve gameplay and robustness.

#### Requirements
Completed program may include any of the following:

- Difficulty levels that adjust allowed attempts.
- Load words from an external file (`words.txt`) if present, falling back to a default list.
- ASCII hangman drawing that progresses with each incorrect guess.
- Replay support so the player can play multiple rounds without restarting the program.
- Write simple unit tests for core functions (e.g. `reveal_letters`, `is_won`).

## 📁 Starter Code

Use the provided starter file `starter-code.py` in this assignment folder as a starting point.

## ▶️ How to Run

Run the game with Python 3:

```bash
python3 starter-code.py
```

## 📤 Submission

Submit your working `starter-code.py` (renamed if you like) and any additional modules or test files. Include brief notes about any enhancements you added.

---

Good luck — have fun building Hangman! :rocket:
```
