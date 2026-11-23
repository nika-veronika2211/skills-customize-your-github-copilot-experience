
# 📘 Assignment: Hangman Game

## 🎯 Objective

Build a Hangman word-guessing game using Python strings, loops, conditionals, and user input.

## 📝 Tasks

### 🛠️ Set Up the Game State

#### Description
Use the starter code to randomly select a secret word and initialize the variables that track the player's guesses.

#### Requirements
Completed program should:

- Randomly select a word from the predefined `words` list.
- Initialize a collection to store letters already guessed.
- Set a maximum number of incorrect guesses.
- Display the hidden word as underscores separated by spaces, such as `_ _ _ _`.

### 🛠️ Implement the Game Loop

#### Description
Create the main game loop that accepts letter guesses and updates the game until the player wins or loses.

#### Requirements
Completed program should:

- Prompt the player to enter a single letter for each guess.
- Reveal correctly guessed letters in the current word display.
- Track incorrect guesses and display the number of attempts remaining.
- End the game when every letter in the word has been guessed.
- End the game when the player runs out of incorrect guesses.
- Display a clear win message or lose message at the end of the game.
