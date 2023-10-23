# slotMachine
interactive python-based slot machine game. 

This project is a Python-based slot machine game. It's a text-based game where players start with an initial balance. They can configure their bets by choosing the number of lines to bet on and the bet amount per line. The game utilizes a 3x3 grid to display symbols randomly selected from a set of predefined symbols, each with its own count and value.

The core logic of the game is in the spin function, which checks for winning combinations on the selected lines and calculates winnings based on the bet and symbol values. It also keeps track of the balance and updates it accordingly.

The game uses functions like deposit, get_lines, and get_bet to handle user input and ensure that the inputs are valid. It also allows players to continue playing by pressing Enter and provides a way to quit the game by typing 'q'. The main function serves as the game loop, providing players with a user-friendly interface to manage their balance and play the game.

This project implements basic game mechanics, input validation, and balance management in Python. It's a fun and interactive way for users to experience a simplified slot machine game.
