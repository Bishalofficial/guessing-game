#  Mini Project: Number Guessing Game (CLI)

This is a simple command-line number guessing game built with Python.  
The computer randomly selects a number between 1 and 100. The user has to guess the number, and the program provides hints if the guess is too high or too low.

---

##  How It Works

The computer picks a number between 1 and 100 using random.randint.
The user guesses the number by typing into the terminal.
After each guess:
  - If it's too high → the program says "Too high!"
  - If it's too low → the program says "Too low!"
  - If it's correct → the program congratulates the user and shows the number of attempts

---

##  How to Run the Program

Make sure Python is installed.
Run the program in terminal:
```bash
python guessing_game.py
