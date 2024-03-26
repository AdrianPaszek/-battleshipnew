Battleship-Python User Documentation
Overview
Battleship-Python is a two-player, turn-based game where each player tries to sink their opponent's fleet of ships by guessing their locations on a hidden board. The game is played in two phases: the positioning phase, where players place their ships on the board, and the shooting phase, where players take turns guessing the locations of the opponent's ships.

Getting Started
Requirements Python 3.x installed on your system. Setup Ensure Python 3.x is installed on your system. Download the Battleship-Python game files to a directory on your computer. Navigate to the directory containing the game files in your terminal or command prompt. Running the Game To start the game, execute the main game file with Python by running the following command in your terminal or command prompt:

python battleship.py
How to Play
The game consists of several components working together to allow a complete game flow from setup to execution. Here's a step-by-step guide on how to play Battleship-Python.

Game Modes
Currently, Battleship-Python supports a Human vs. Human mode where two players compete against each other.

Game Flow
Start Screen:
Upon starting the game, players are greeted with a menu. Select the game mode to proceed.

Positioning Phase:
Each player takes turns to position their ships on the board. The board size is 5x5, and the number and size of ships are determined based on the board size. Players are prompted to enter coordinates for placing their ships. Valid coordinates and ship orientation (horizontal or vertical) are required. Once all ships are placed, the game progresses to the shooting phase.

Shooting Phase:
Players take turns to guess the location of the opponent's ships by entering coordinates. A hit on a ship is marked, and a miss is indicated as well. If a ship is completely hit, it is considered sunk. The game announces when a ship is sunk. The game continues until all ships of one player are sunk, determining the winner.

Controls and Commands
During the positioning phase, enter the coordinates (e.g., "A1") and orientation ("H" for horizontal, "V" for vertical) for your ships. During the shooting phase, enter the coordinates (e.g., "B2") to fire at the opponent's board.

Ending the Game
The game concludes when all of one player's ships are sunk. The winner is announced, and players are given the option to exit the game.

Tips for Players
Think strategically about the placement of your ships to make it harder for your opponent to guess their locations. Pay attention to the hits and misses to narrow down the possible locations of your opponent's ships. Use the pause between phases to plan your next moves.

Enjoy playing Battleship-Python, and may the best strategist win!
