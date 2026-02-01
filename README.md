# Python Hangman Game 🐍

A terminal-based Hangman game built as part of the **#100DaysOfCode** Python Challenge (Day 7).

## 🚀 How it Works
* **Random Word Selection**: The game pulls a random word from a custom library.
* **Interactive UI**: Features ASCII art that updates as the player loses lives.
* **Smart Logic**: Prevents the player from losing lives for repeating a guess.

## 🛠️ Concepts Used
* **Modularity**: Importing variables across multiple Python files (`main.py`, `hangman_art.py`, `hangman_words.py`).
* **State Management**: Using `while` loops and lists to track game progress and lives.
* **User Experience**: Handling case-insensitive inputs and providing visual feedback.

## 📂 Project Structure
* `main.py`: The core game engine.
* `hangman_art.py`: Contains the game logo and the hanging man stages.
* `hangman_words.py`: A library of potential words.