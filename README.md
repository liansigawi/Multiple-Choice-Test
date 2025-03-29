# Word Guessing Game (Java)

A simple console-based word guessing game written in Java. The user has up to 10 attempts to guess a randomly chosen word, one letter at a time.

---

## 🎯 Project Description

This project implements a basic **Hangman-style** word guessing game:
- A word is randomly selected from a predefined list.
- The user guesses one letter per turn.
- The game keeps track of remaining letters and prevents repeated guesses.
- The game ends when the word is guessed or after 10 incorrect attempts.

---

## 🧱 Project Structure

- `WordPool.java` – contains a pool of words used in the game.
- `ChoosenWord.java` – selects a random word from the word pool.
- `Game.java` – handles game logic, user input, and UI flow.

---

## 🖥️ How to Run

Make sure you have Java installed. Then compile and run:

```bash
javac Game.java
java Game
