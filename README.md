# 🔠 Hangman Game in C

This is a fun command-line **Hangman game** written in C, where players can choose from two categories: **Fruits** and **Animals**. It includes a **limited number of attempts**, a **visual Hangman**, and even a **clue system** to help the player guess the word!

---

## 🎮 Features

- 🧠 Choose from two categories:
  - **Fruits**
  - **Animals**
- 🧱 Visual Hangman built using ASCII graphics
- ❓ One-time **clue system**: reveals a random letter from the word
- 🔁 Words are shuffled to ensure randomness in each play
- 🚫 Limited to 5 wrong guesses
- 🔄 Input validation and repeated guess checks
- 👀 Tracks and displays the current state of the guessed word

---

## 🧱 How It Works

1. User selects a category.
2. A random word from the selected category is picked and shuffled.
3. The user guesses letters one at a time.
4. Incorrect guesses result in the hangman gradually being drawn.
5. The user has **one chance to use a clue** (reveals one random letter).
6. The game ends when the player either:
   - Guesses all letters correctly ✅
   - Reaches the maximum number of wrong guesses ❌

---

## 🧾 Files

```

hangmangame.c        # Main game logic and UI

````

---

## 🛠️ How to Compile and Run

### On Linux / Mac:
```bash
gcc hangman_game.c -o hangman
./hangman
````

### On Windows (using GCC):

```bash
gcc hangman_game.c -o hangman.exe
hangman.exe
```

---

## 📌 Sample Gameplay

```
Welcome to Hangman!
Select a category:
1. Fruits
2. Animals
Enter the category number: 1

--- Fruits Category ---
Welcome to Hangman!

Word: _ _ _ _ _

Guess a letter or type 'clue' for a hint (you have 1 clue): a
Correct guess!

...

Congratulations! You guessed the word: mango
```

---

## 📈 Future Improvements

* Add more categories (e.g., Countries, Sports)
* Add difficulty levels (easy, medium, hard)
* Save high scores or game history
* Add multiplayer or scoring system

---

## 👩‍💻 Developed By

**Varri Navya**
Feel free to connect on [GitHub](https://github.com/Navyavarri10) 😊

---
