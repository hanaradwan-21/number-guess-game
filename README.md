Number Guessing Game 🎯

A simple *Number Guessing Game* written in Python!  
The program generates a random number between *1 and 10*, and you have to guess it within a limited number of attempts.

---

## Features
- Uses random.randint(1, 10) to generate a random number.
- Lets the user choose the maximum number of attempts.
- Tells the player if their guess is:
  - *Too high* 🔼  
  - *Too low* 🔽  
  - *Correct!* 🎉  
- Displays the total number of attempts used when you guess correctly.

---

## How to Run
1. *Make sure you have Python 3 installed*:
   ```bash
   python --version

2. Run the program:

python main.py


3. Follow the instructions in the terminal and try to guess the number!




---

Example Output

Enter the number of attempts: 3
Guess the number between 1 and 10: 5
Too low! Try again.
Guess the number between 1 and 10: 8
Too high! Try again.
Guess the number between 1 and 10: 7
Correct! You guessed it in 3 attempts!


---

Requirements

Python 3.x



---

Future Improvements

Add difficulty levels (1-10, 1-50, 1-100)

Show a history of previous guesses

Add color to the console output using colorama

Make it a two-player game
