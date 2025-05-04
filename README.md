
# Hangman Game

A classic **Hangman** word guessing game built using **Python** and **Pygame**.

## 🕹️ Game Overview

Guess the hidden word by clicking on letters. If you guess wrong too many times, the hangman is completed and the game ends. Guess all the letters correctly before running out of attempts to win!


## 🚀 Features

* Interactive graphical interface using Pygame
* Random word selection from a predefined list
* Visual representation of hangman stages with images
* Clickable alphabet buttons
* Displays win/loss message

## 🛠️ Technologies Used

* Python 3
* Pygame

## 📂 Project Structure

```
|-- hangman.py
|-- img_9.png         # Game icon
|-- img_21.png        # Initial hangman image
|-- img_22.png        # Hangman stage images
|-- img_23.png
|-- img_24.png
|-- img_25.png
|-- img_26.png
```

## ⚙️ Installation & Setup

1. **Clone the repository**

```bash
git clone <repository-url>
cd <project-directory>
```

2. **Install dependencies**

```bash
pip install pygame
```

3. **Run the game**

```bash
python hangman.py
```

## 🎮 How to Play

* The game will randomly select a word.
* Click on the letter buttons to guess a letter.
* If the letter is in the word, it will be revealed.
* If the letter is not in the word, part of the hangman will be drawn.
* You have 6 incorrect guesses before you lose the game.
* The game will display "YOU WON!" or "YOU LOST!" depending on the outcome.

## 📝 Word List

The default word list is:

```
['PYGAME', 'PYTHON', 'JAVA', 'HELLO', 'WORLD', 'HANGMAN', 'TIME', 'TURTLE', 'RANDOM']
```

You can modify or extend the word list directly in the `words` variable inside `hangman.py`.

## 📌 Notes

* Ensure all image files (`img_9.png`, `img_21.png`, etc.) are in the same directory as `hangman.py`.
* The game uses **Arial** font; ensure system compatibility (most systems have it by default).

## 🙌 Acknowledgements

This project was built for educational and recreational purposes using Python and Pygame.

## 📃 License

This project is licensed under the MIT License. Feel free to use and modify it!

---

> *Happy Playing!* 🎉
