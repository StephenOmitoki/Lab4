# Lab4

Stephen Omitoki

Lab4_1
Overview:
This program simulates the game of Craps with wagering features. The player starts with 100 credits and can place bets on each game round. The game involves rolling two dice, and the outcome determines whether the player wins or loses. The player can keep playing until they either run out of credits or choose to quit.

How It Works:
The player places a bet before each round.
The dice are rolled, and the sum is calculated.
If the sum is 7 or 11 on the first roll, the player wins.
If the sum is 2, 3, or 12 on the first roll, the player loses.
If any other number is rolled, that number becomes the " target point." The player continues rolling until they either roll the target point again (win) or roll a 7 (lose).
The game keeps track of the player's balance, updating it based on the result of each round.


Key Variables:
playerBalance: Tracks the player's current credits (starts at 100).
betAmount: The amount wagered on each game.
targetPoint: The number the player must roll again to win if they don’t win or lose on the first roll.

Functions:
rollDice: Simulates rolling two dice and returns the sum.
playerWins: Updates the player's balance and announces a win.
playerLoses: Announces a loss and keeps track of the remaining balance.
playGame: The main game logic that rolls the dice and checks for wins or losses.

Running the Program:
The player will be prompted to place a wager.
The dice will be rolled, and the result will be displayed.
Depending on the result, the game will continue or end the round.
The player can choose to play again or quit.
The game ends automatically if the player's balance reaches zero.

Requirements:
C++ compiler.



Lab4_2

Game of Life

Overview:
This program simulates the Game of Life, a grid-based game where cells live or die based on the number of live neighbors they have. The game follows simple rules to determine whether each cell in the grid lives, dies, or becomes alive in the next generation.

How to Run:
Input the Initial Live Cells:

After running the program, you'll be prompted to enter the coordinates of live cells.
Enter the x and y coordinates (e.g., 2 3) for each live cell.
To stop entering coordinates, input -1 -1.


After entering the initial configuration, the grid will display the first generation of cells.
The program will prompt you to press any key to view the next generation or press q to quit.


Game Rules:

Live Cell:
Lives if it has 2 or 3 live neighbors.
Dies if it has fewer than 2 (underpopulation) or more than 3 (overcrowding) neighbors.

Dead Cell:
Becomes alive if it has exactly 3 live neighbors.

Grid Size:
The grid is 10x10 by default. Cells outside this range are ignored.

Requirements:
C++ compiler

Quit the Program:
To quit at any time, press q.

Files:
main.cpp: Contains the main logic of the program, user interaction, and game loop.
gameoflife.cpp: Handles the game logic, grid updates, and neighbor counting.

