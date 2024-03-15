# Guess The Number Game 

##Description

Guess The Number is a simple and interactive number-guessing game where the user try to guess a randomly
generated number by the computer within a specified range depending on user's chosen game level. This game was developed using Python. 
The game offers 3 levels of difficulty that Users have a choice to choose from: easy (in this level, you will only guess 
between numbers 1-10), medium (in this level, you will only guess between numbers 1-100) or hard (in this level, 
you will only guess between numbers 1-1000). After the game ends, the game will be able to tracks the player's 
wins and losses and allow user the options to play again or end the game. 

##Prerequisites

Anaconda Navigator (optional)
Jupyter Notebook (optional)
Import random within the code to allow to generate the random number

##Getting started

1. Open Anaconda Navigator
2. Launch Jupyter Notebook
3. Create a new notebook or open an existing one
4. Copy and paste the game code into the notebook cell
5. Run the cell to start the game

##Instructions

1. Run the main() fucntion to start the game
2. User enters their name to begin the game. 
3. Select a game level: easy, medium or hard
4. The computer will randomly choose a number with the specified level depending on level chosen
5. Guess the number by entering your guess
6. Receive feedback on each guess: 
 -- 'too high' if the number is higher than the correct number
 -- 'too low' if the number is lower than the correct number
 -- 'Correct! your number is a match' if your guess is correct
7. Keep guessing until you correctly guess the number or run out of attempts
8. The game will update your total wins and losses after each game
9. If you guess the correct number within the given attempts, your wins will increase.
10. If you exhaust all attempts without guessing the correct number, your losses will increase, 
and the correct number will be revealed.
11. You can choose to play again after each round to improve your score and beat your high score.
12. The game will keep track of your wins and losses across multiple rounds, allowing you to play 
as many times as you like.

##Rules

In easy, the range is 1 to 10 and you have 3 attempts
In medium, the range is 1 to 100 and you have 5 attempts
In hard, the range is 1 to 1000 and you have 10 attempts
You can only input numeric guesses within the specified range

Have fun and enjoy the game!

