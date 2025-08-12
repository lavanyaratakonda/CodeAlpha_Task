# CodeAlpha_Task
Hangman Game (Python + GUI)

This is a Python implementation of the **Hangman Game** in two versions:  
1. **Console-based version**  
2. **GUI version using Tkinter**  

The player has 6 lives to guess the hidden word, letter by letter. Each wrong guess decreases a life, and the hangman drawing progresses until the game ends.

 Project Structure
```
📁 Hangman-Game/
 ├── hangman_game.py      # Console version of Hangman
 ├── hangman_gui.py       # GUI version using Tkinter
 ├── hangman_stages.py    # ASCII art for Hangman stages
 ├── word_file.py         # Word list for the game
```


How to Run

**1️⃣ Console Version**
```bash
python hangman_game.py
```
- Guess letters via terminal input.
- You win if you guess all letters before running out of lives.

---

**2️⃣ GUI Version**
```bash
python hangman_gui.py
```
- Click **Guess** after entering a letter.
- Click **Reset Game** to start again.

---

Requirements
- Python 3.x
- Tkinter (comes pre-installed with Python)

---

Features
Two gameplay modes (Console & GUI)  
Random word selection from a word list  
Lives counter with hangman drawing  
Input validation & feedback messages in GUI  
Option to reset the game in GUI version  

---

 Screenshots

**Console Version:**
```
Guess a letter: a
['_', 'a', '_', 'a', '_', 'a']
```

**GUI Version:**  
*(Hangman drawing + letter input + win/lose popups)*

---

Future Improvements
- Add difficulty levels  
- Support multiplayer mode  
- Allow custom word lists from a file  

---

License
This project is open-source and free to use for educational purposes.  
