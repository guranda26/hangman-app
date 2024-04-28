# Hangman Game

Hangman is a digital version of the classic word-guessing game. The objective is to guess the hidden word by suggesting letters within a certain number of guesses.

## Project Description

This project is a simple interactive game designed to be played on any device with a web browser. It features a virtual keyboard for letter selection and updates the display based on the player's guesses, showing the progress of the hangman as incorrect guesses accumulate.

## Game Rules

- **Game Structure:** The game consists of a gallows and a quiz section that includes a question and a hidden word represented by underscores. Each incorrect guess adds a part to the hangman on the gallows, and each correct guess reveals the corresponding letters in the word.
- **Input Methods:** Players can use both a virtual on-screen keyboard and their physical keyboard to enter guesses.
- **Gameplay Flow:**
  - Correct guesses replace the respective underscores with the guessed letter.
  - Incorrect guesses add a body part to the gallows and update the incorrect guesses counter.
  - Used letters become disabled in the UI to prevent reselection.
  - The game ends either by correctly guessing the word or filling the gallows with all six body parts (head, body, both arms, and both legs).
- **End of Game:** A modal appears showing a win or loss message, the correct word, and a "play again" button to restart the game.
- **Replayability:** Upon starting a new game, the gallows are cleared, a new question and word are presented, and the incorrect guesses counter resets.

## Functional Requirements

- **Adaptive Design:** The interface adapts to different screen sizes (desktop, tablet, mobile) ensuring a consistent and usable layout across devices.
- **Dynamic Content:** All game elements are dynamically generated via JavaScript, with the initial HTML body being empty.
- **Random Selection:** Each game randomly selects from at least 10 predefined question-answer pairs, ensuring varied gameplay.

## Setup and Installation

1. Clone the repository:
2. Open `index.html` in your web browser to start playing.
   
## Technologies Used

- HTML5
- CSS3 (with responsive design)
- JavaScript (for game logic and UI manipulation)

## Screenshots

**Desktop View:**

![Desktop View](https://ibb.co/VQ2NqsL)
![Mobile View](https://ibb.co/r65DGTh)

