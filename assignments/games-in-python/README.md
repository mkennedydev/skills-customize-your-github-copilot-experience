
# 📘 Assignment: Hangman Game

## 🎯 Objective

Build a word-guessing game in Python that uses string manipulation, loops, conditionals, user input, and random selection. The player should reveal a hidden word before using all available incorrect guesses.

## 📝 Tasks

### 🛠️ Set Up the Game

#### Description

Complete the game setup using the provided list of words and initialize the variables needed to track the hidden word, guessed letters, and incorrect guesses.

#### Requirements

Completed program should:

- Randomly select one word from the provided `words` list.
- Store the letters guessed by the player.
- Set a maximum number of incorrect guesses and track the remaining attempts.

### 🛠️ Implement the Guessing Game

#### Description

Write the main game loop so the player can guess letters, see their progress, and receive a result when the game ends.

#### Requirements

Completed program should:

- Display the hidden word as underscores for letters that have not been guessed.
- Accept a letter guess and update the game state for correct and incorrect guesses.
- End when the player reveals the entire word or uses all incorrect guesses.
- Display a clear win or lose message at the end of the game.
