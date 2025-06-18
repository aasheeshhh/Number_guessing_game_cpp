
#  Number Guessing Game (C++)

##  Description
A simple command-line number guessing game written in C++.
The computer selects a random number between 1 to 10 and the player has 5 chances to guess it.
After each guess, the program hints whether the correct number is higher or lower.
The game ends when the player guesses correctly or runs out of chances.

##  Features
- Random number generation using rand() and time()
- Input validation with std::cin.fail()
- Hints: "higher" or "lower" after each guess
- Max 5 attempts per game
- Displays win/loss message and number of attempts

##  Functions / Logic
| Functionality         | Purpose                                      |
|:---------------------|:---------------------------------------------|
| rand() % 10 + 1       | Generates a random number between 1 and 10   |
| do-while loop         | Runs the game until win or 5 failed attempts |
| std::cin.fail()       | Validates player input (checks invalid values) |

## 🛠 Tools & Technologies
- C++
- g++ compiler
- Libraries: iostream, ctime
 

##  Notes
- Max of 5 chances allowed
- Displays correct number if player loses
- Input validated to ensure numeric entry

##  Future Scope
- Add difficulty levels (easy, medium, hard)
- Track number of games won or lost
- Option to play again without restarting program
  
