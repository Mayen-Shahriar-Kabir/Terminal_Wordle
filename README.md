# 🟩🟨 Terminal Wordle: A Python Logic Game

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/<Mayen-Shahriar-Kabir>/<Terminal_Wordle>/blob/main/Terminal_Wordle.ipynb)

A fully functional, terminal-based clone of the popular game Wordle, built entirely in Python. This project was originally created during my first semester to explore foundational programming concepts and demonstrates how basic logic can be used to build engaging, interactive applications.

You can play the game instantly in your browser by clicking the **Open in Colab** badge above.

### 🎮 How to Play
1. Run the code block in Google Colab.
2. Enter a valid 5-letter word when prompted. The game gives you exactly 5 guesses[cite: 1].
3. The terminal will output your guess with color-coded feedback[cite: 1]:
   * **Green:** The letter is in the word and in the correct spot.
   * **Yellow:** The letter is in the word but in the wrong spot.
   * **Red:** The letter is not in the word.
4. An interactive keyboard updates dynamically at the bottom of the screen to help you track available letters[cite: 1].

### 🧑‍🏫 Pedagogical Value (For Beginners)
I open-sourced this project to serve as a practical learning tool for computer science beginners. Building a text-based game is one of the most effective ways to understand core programming paradigms. By reviewing this code, students can learn:

* **Control Flow & Loops:** Utilizing `while` loops to manage the 5-guess limit and `for` loops to iterate through the characters of the strings[cite: 1].
* **Conditional Logic (If/Else):** Implementing the core game rules to check for exact character matches, partial matches, or misses to assign the correct ANSI color codes[cite: 1].
* **String Manipulation:** Dynamically updating the visual ASCII keyboard by replacing characters based on the user's progression[cite: 1].
* **Input Validation:** Ensuring the user's input is exactly 5 letters and only contains alphabetic characters before processing the turn[cite: 1].
* **Library Imports:** Using `random.randint` to select a target word from a predefined list and `IPython.display.clear_output` to refresh the terminal for a clean user interface[cite: 1].
