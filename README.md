# Tic-Tac-Toe Game in C++

## Description

This is a simple console-based Tic-Tac-Toe game implemented in C++. The game allows two players to take turns playing on a 3x3 board. The game checks for a winner after each move and announces the result at the end.

## Features

- Two-player mode
- Board display after each move
- Input validation to ensure valid moves
- Checks for a winner or tie

## Prerequisites
   To compile and run this program you will need<br>
      -A C++ compiler (e.g., ``clang++``, ``g++``)<br>
      -A terminal or command prompt

## How to Run

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/Unknown-333/TicTacToe.git

2.**Compie and Run**

   ``g++ -o TicTacToe main.cpp`` ``./main``

## Code Explanation

1.**Board Initialization**: The game board is initialized as a 3x3 array of characters, all set to a space character ' '.

2.**Game Loop**: The game runs for a maximum of 9 moves or until a winner is found. After each move, the board is printed, and input is collected from the current player.

3.**Input Validation**: The game checks if the input is within the valid range and whether the chosen cell is empty. Invalid inputs are rejected, and the user is prompted to try again.

4.**Winner Check**: The game checks for winners by examining rows, columns, and diagonals. If three consecutive cells in any of these directions contain the same player's mark ('X' or 'O'), that player is declared the winner.

5.**End of Game**: If a winner is found, a message is displayed. If no winner is found after 9 moves, the game is declared a tie.

## Sample Output

```
   |   |   
   |   |   
___|___|___
   |   |   
   |   |   
___|___|___
   |   |   
   |   |   
   |   |   

Current Player is X
Enter r c from 0-2 for row and column: 0 0

   |   |   
 X |   |   
___|___|___
   |   |   
   |   |   
___|___|___
   |   |   
   |   |   
   |   |   

Current Player is O
Enter r c from 0-2 for row and column: 1 1

   |   |   
 X |   |   
___|___|___
   | O |   
___|___|___
   |   |   
   |   |   
   |   |   

Current Player is X
Enter r c from 0-2 for row and column: 0 1

   |   |   
 X | X |   
___|___|___
   | O |   
___|___|___
   |   |   
   |   |   
   |   |   

Current Player is O
Enter r c from 1 0

   |   |   
 X | X |   
___|___|___
 O | O |   
___|___|___
   |   |   
   |   |   
   |   |   

Current Player is X
Enter r c from 0-2 for row and column: 0 2

   |   |   
 X | X | X 
___|___|___
 O | O |   
___|___|___
   |   |   
   |   |   
   |   |   

Player X is the winner!
```

## Contributing
   Feel free to open issues or submit pull requests for improvements, bug fixes, or additional features. Contributions are welcome!

