# 🎮 Hangman Game

A simple text-based **Hangman Game** developed in **Python** as part of the **CodeAlpha Python Programming Internship**.

## 📖 Project Overview

The Hangman Game is a classic word guessing game where the computer randomly selects a word from a predefined list. The player must guess the word one letter at a time. Each incorrect guess reduces the number of remaining chances. The game ends when the player either guesses the word correctly or runs out of attempts.

## ✨ Features

- 🎲 Randomly selects a word from a predefined list
- 🔤 Guess one letter at a time
- ❌ Maximum of 6 incorrect guesses
- ✅ Displays correctly guessed letters
- 🏆 Win and Lose messages
- 🖥️ Console-based and beginner-friendly

## 🛠️ Technologies Used

- Python 3
- Random Module
- VS Code (or any Python IDE)

## 📂 Project Structure

```
CodeAlpha_Hangman_Game/
│── hangman.py
│── README.md
```

## ▶️ How to Run

### 1. Clone the repository

```bash
git clone https://github.com/your-username/CodeAlpha_Hangman_Game.git
```

### 2. Open the project folder

```bash
cd CodeAlpha_Hangman_Game
```

### 3. Run the program

```bash
python hangman.py
```

## 🎯 How to Play

1. The computer randomly selects a word.
2. Guess one letter at a time.
3. If the guessed letter is correct, it appears in the word.
4. If the guessed letter is incorrect, one chance is lost.
5. You have a maximum of **6 incorrect guesses**.
6. Guess all letters correctly to win the game.

## 💻 Sample Output

```
===== HANGMAN GAME =====

Word: _ _ _ _ _ _

Enter a letter: p

Word: p _ _ _ _ _

Enter a letter: y

Word: p y _ _ _ _

...

🎉 Congratulations! You guessed the word: python
```

## 📚 Python Concepts Used

- Variables
- Lists
- Strings
- Loops (`while`, `for`)
- Conditional Statements (`if`, `else`)
- Functions
- User Input (`input()`)
- Random Module (`random.choice()`)

## 🎯 Learning Outcomes

Through this project, I learned:

- How to use the `random` module
- Working with loops and conditions
- String manipulation
- List operations
- Building an interactive console application
- Problem-solving using Python

## 🚀 Future Improvements

- Add difficulty levels (Easy, Medium, Hard)
- Read words from a text file
- Display ASCII Hangman graphics
- Add score tracking
- Allow multiple rounds of gameplay

## 👩‍💻 Author

**Vedika Rajesh Gosavi**

B.Sc. (Voc) Data Science & Artificial Intelligence

## 🏢 Internship

This project was completed as part of the **CodeAlpha Python Programming Internship**.

## 📜 License

This project is created for educational and internship purposes.
