# 🎯 Number Guessing Game in Python

## 📌 About the Project
The **Number Guessing Game** is a simple Python project in which the computer randomly selects a number between 1 and 100. The player has to guess the correct number.

After each guess, the game provides feedback:
- If the guess is too small, it asks the player to choose a bigger number.
- If the guess is too big, it asks the player to choose a smaller number.
- If the guess is correct, the player wins.
- The player can quit the game at any time by entering `Q`.

## ✨ Features
- Random number generation.
- Interactive user input.
- Helpful hints for every incorrect guess.
- Quit option using `Q`.
- Simple and beginner-friendly Python code.

## 🛠️ Technologies Used
- **Language:** Python
- **Module:** `random` (built-in Python module)

## 📂 Project Structure

```text
Number-Guessing-Game/
│
├── game.py
└── README.md
```

## 🚀 How to Run the Project

### Step 1: Install Python
Download and install Python from the official website:

https://www.python.org/downloads/

### Step 2: Download or Clone the Project
Download the project files and open the project folder in VS Code or your terminal.

### Step 3: Run the Program
Open the terminal in your project folder and execute:

```bash
python game.py
```

If that command does not work on Windows, try:

```bash
py game.py
```

### Step 4: Play the Game
- Enter a number between 1 and 100.
- Follow the hints to guess the correct number.
- Type `Q` to quit the game.

## 💻 Example Output

```text
Guess the target or Quit (Q): 50
Your number was too small. Take a bigger guess.

Guess the target or Quit (Q): 75
Your number was too big. Take a smaller guess.

Guess the target or Quit (Q): 63
Success: Correct Guess!!
------ GAME OVER ------
```

*Note: The target number is generated randomly, so the output will vary each time you play.*

## 🎓 Learning Outcomes
By building this project, you can learn:
- How to use Python's `random` module.
- How to take user input using `input()`.
- How to use `while` loops.
- How to apply `if`, `elif`, and `else` conditions.
- How to convert strings into integers.
- How to use `break` to exit a loop.

## 🔮 Future Improvements
- Add a maximum number of attempts.
- Display the number of guesses taken.
- Add input validation for invalid entries.
- Include difficulty levels such as Easy, Medium, and Hard.

## 👨‍💻 Author : Dilip kumar
Created as a beginner-friendly Python programming project.

