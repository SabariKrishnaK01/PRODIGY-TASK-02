# PRODIGY-TASK-02 - 🔢 Number Guessing Game

An interactive and beginner-friendly number guessing game developed in Python. The program randomly selects a number within a predefined range (e.g., 1–100), and the user must guess it. After each attempt, the program provides feedback indicating whether the guess was too high, too low, or correct.

🛠️ Features

 - Random number generation to ensure unpredictability
 - User interaction via input prompts
 - Dynamic feedback after each guess (Too high / Too low)
 - Loop-based gameplay allowing multiple attempts
 - Attempt counter to track how many guesses were made
 - Input validation to prevent crashes on invalid entries
 - Game ends automatically once the correct number is guessed

🧠 Concepts Demonstrated

 - random.randint() for generating random integers
 -  while loops for continuous guessing until correct
 -  if / elif / else statements for decision-making
 -  Input/output handling using input() and print()
 -  Exception handling (optional enhancement using try-except)
 -  Basic control flow and logic building in Python

 💻 Sample Output - 🎮 Welcome to the Number Guessing Game!
     I'm thinking of a number between 1 and 100.
     Enter your guess: 50
     Too low!

     Enter your guess: 75
     Too high!

     Enter your guess: 63
     Correct! 🎉 You guessed the number in 3 attempts.
