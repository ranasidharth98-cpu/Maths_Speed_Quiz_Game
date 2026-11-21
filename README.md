# Math Speed Quiz Game

A timed command-line mental math quiz game built in Python. The script generates random arithmetic problems, requires the correct answer before advancing, and measures total completion time across a set number of rounds.

## Features

* **Randomized Arithmetic Prompts:** Generates addition (`+`), subtraction (`-`), and multiplication (`*`) expressions using operands between `5` and `15`.
* **Strict Answer Loop:** Prompts repeatedly for the current question until a matching answer is entered.
* **Stopwatch Timing:** Uses `time.time()` to measure elapsed time from starting the quiz to completing all `12` problems, rounded to two decimal places.
* **Configurable Constants:** Easy-to-adjust module-level constants (`OPERATORS`, `MIN_OPERAND`, `MAX_OPERAND`, and `TOTAL_PROBLEMS`).

## How It Works

1. **Problem Generation:** Picks two random integers in and a random operator, formats the expression string, evaluates the result, and returns the answer.
2. **Quiz Loop:** After the user presses `Enter`, the start timestamp is recorded and the loop runs `TOTAL_PROBLEMS` times. Each question repeats until itself until the right answer is given.
3. **Results:** Once all problems are solved, the script calculates the total time taken and prints the total completion time in seconds.

## How to Run in Google Colab

Step 1: You need a web browser (Chrome, Safari, Edge, Firefox) and a Google account (to log into Google Colab)

Step 2: Open your web browser and go to colab.new.

Step 3: Copy the complete Python code block for the Math Speed Quiz Game.

Step 4: Go back to the Google Colab tab you opened in Step 2. Click inside the large empty text box. Paste the entire block of code you just copied.

Step 5: Look at the left side of the box where you pasted the code. You will see a round Play button. Click that Play button. Python will start running the script in the cloud.

Step 6: Look directly beneath the code box. A small text line will appear saying: "Press enter to start" Click your mouse inside the output box right below that text, and press your keyboard's Enter key. The stopwatch starts! Solve each math problem as it pops up, type your answer, and hit Enter. Once you finish all 12 problems, the screen will display your final score and total completion time in seconds.
