Slot Machine Game


A simple text-based slot machine game written in Python. The game allows the player to deposit money, bet on multiple lines, spin the slot machine, and win or lose based on the results.

Table of Contents:
Features
Installation
How to Play
Game Logic
Contributing
License


Features

Players can deposit money to start.
Players can bet on up to 3 lines at once.
Randomly generated slot machine spins.
Different symbols with varying values.
Displays winnings and keeps track of the player's balance.


Installation
Prerequisites
Python 3.x
A terminal or command line interface


Steps Clone the repository:

bash
Copy code
git clone https://github.com/yourusername/slot-machine-game.git
cd slot-machine-game
Run the game: You can run the game by executing the following command in your terminal:

bash
Copy code
python slot_machine.py
How to Play
Deposit Money: When the game starts, you will be prompted to deposit money. This is your starting balance.

Choose Number of Lines: Choose the number of lines you want to bet on (between 1 and 3).

Place Bet: You will then be asked how much to bet on each line. You can bet between $1 and $100 on each line.

Spin the Slot Machine: After placing the bet, the slot machine will spin, and you'll see the results.

Check Winnings: If you win, your balance will increase based on the symbols. If you lose, the bet amount is subtracted from your balance.

Quit Anytime: You can press 'q' to quit the game at any point.

Game Logic
The slot machine consists of 3 rows and 3 columns. The symbols that can appear on the slot machine are:

A (highest value)
B
C
D (lowest value)
Each symbol has a different frequency of appearing, and each has a different payout value.

Symbol Frequencies:

A appears 2 times
B appears 4 times
C appears 6 times
D appears 8 times
Payout Values:

A = 5x bet
B = 4x bet
C = 3x bet
D = 2x bet
Winning is determined if the same symbol appears across all columns in any row. You win the value of the symbol multiplied by your bet for that row.

Example Gameplay

Deposit: $100
Bet on 3 lines, $5 per line.
Total bet = 3 * 5 = $15
Spin the slot machine.
If you win, the winning amount is added to your balance.
Keep playing until you run out of money or choose to quit!
Contributing
Feel free to open an issue or submit a pull request if you'd like to contribute to this project.

License:
This project is open source and available under the MIT License.
