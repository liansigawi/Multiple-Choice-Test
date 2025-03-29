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
```
---

## 🕹️ Example Gameplay
Welcome to Word Guessing Game!
Guess the word one letter at a time.
Remaining letters: abcdefghijklmnopqrstuvwxyz
Enter a letter: a
Incorrect guess. Try again.
Remaining letters: bcdefghijklmnopqrstuvwxyz
Enter a letter: e
Correct guess!
Word: __e__e
...
Congratulations! You've guessed the word: green
Number of guesses: 7
Do you want to play again? (yes/no):

---
## 🧠 Concepts Practiced
-Object-Oriented Programming (OOP)

-Arrays and String manipulation

-Randomization

-Console I/O and input validation

-Basic game loop structure


