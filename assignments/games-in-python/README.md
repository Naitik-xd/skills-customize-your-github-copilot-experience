
# 📘 Assignment: Hangman Game

## 🎯 Objective

Build a word-guessing game using Python strings, loops, conditionals, user input, and random selection. Practice converting a game description into a complete, interactive program.

## 📝 Tasks

### 🛠️ Set Up the Game

#### Description
Prepare the word list and choose a secret word for the player to guess.

#### Requirements
Completed program should:

- Define a predefined list containing at least 5 words.
- Randomly select one word from the list.
- Convert the selected word to lowercase.
- Create a display that shows one underscore for each letter in the selected word.

### 🛠️ Process Player Guesses

#### Description
Repeatedly ask the player to guess a letter and update the game based on each guess.

#### Requirements
Completed program should:

- Accept a single letter from the user for each guess.
- Display the word's current progress, with guessed letters revealed and other letters shown as underscores.
- Track correctly guessed letters so repeated guesses do not alter the incorrect-guesses remaining.
- Track incorrectly guessed letters and the number of attempts remaining.
- Ignore or prompt the player again for input that is not a single alphabetic letter.

### 🛠️ End and Display the Result

#### Description
Finish the game when the player guesses the word or uses all available attempts.

#### Requirements
Completed program should:

- End the game when every letter in the secret word has been guessed.
- End the game when the incorrect-guesses remaining reaches zero.
- Display a clear win message and the secret word when the player wins.
- Display a clear lose message and reveal the secret word when the player loses.
