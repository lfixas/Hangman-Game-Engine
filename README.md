# Hangman Game Engine

Welcome to the Hangman Game Engine! This Python-based Hangman game allows players to guess words and phrases within a limited number of attempts. The game provides a graphical interface and features such as rules, best scores, and a timer.

<div align="center"><img src="https://github.com/lfixas/Hangman-Game-Engine/blob/main/github/Github%20Hangman%20Animation.gif" alt="Hangman Game Engine" width="auto" height="288"/></div>

## Getting Started

1. **Clone the Repository:**
   ```bash
   git clone git@github.com:lfixas/Hangman-Game-Engine.git
   cd hangman-game
   ```
   
2. **Install Dependencies:**
   ```bash
   pip install customtkinter
   ```
3. **Run the Game:**
   ```bash
   python "Hangman Game Engine V1.py"
   ```

## Features

- **New Game**: Start a new Hangman game with a randomly selected word.

- **Rules**: View the rules of the Hangman game to understand how to play.

- **Best Scores**: Check the top 10 best scores, including the word, time taken, and lives used.

- **Timer**: Track the time taken to complete the game.

- **Difficulty Level**: Adjust the difficulty level from 11 to 1 (the number of lives).

## How to Play

1. Click "``New Game``" to start a new Hangman game.

2. Guess letters or the entire word to reveal the hidden word.

3. View the rules for more details on how to play.

4. Check the best scores to see how you compare with other players.

5. Have fun playing Hangman!

## Game Interface

- **Main Frame**: Displays the Hangman game interface, including the word, results, and a picture of the Hangman.

- **Sidebar**: Provides options for starting a new game, viewing rules, and checking best scores.

- **Alphabet Buttons**: Click on the alphabet buttons to make letter guesses.

- **Timer**: Displays the time taken to complete the game.

## Game Rules

The Hangman Game follows these rules:

- **Objective**: Guess the hidden word or phrase correctly before running out of attempts.

- **Number of Attempts**: Players have a limited number of attempts to reveal the hidden word.

- **Guessing a Letter**: Players guess letters, and correct guesses reveal the letter's position(s) in the word.

- **Word Completion**: The game continues until the players either guess the entire word or run out of attempts.

- **Winning**: Players win by guessing the word within the allowed attempts.

- **Losing**: Players lose if they use up all their allowed guesses without correctly guessing the word.

## Author
- **Lucas Fixari**
  - GitHub: [github.com/lfixas](https://github.com/lfixas)

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## Acknowledgments

- Special thanks to the creators of the [customtkinter](https://pypi.org/project/customtkinter/) library for the graphical user interface.

Feel free to contribute to the Hangman Game Engine and enjoy playing!
