# codsoft_taskno-4

# Rock-Paper-Scissors Game

The Rock-Paper-Scissors game is a classic hand game usually played between two people, where each player simultaneously forms one of three shapes with an outstretched hand. The possible shapes are "rock" (a closed fist), "paper" (an open hand), and "scissors" (a fist with the index and middle fingers extended, forming a V).

## Functionality

- The game is played against an AI opponent named "ALEXA".
- Players can choose their move by entering "Rock", "Paper", or "Scissors".
- The AI opponent randomly selects one of the three moves.
- The game determines the winner based on the classic rules: Rock beats Scissors, Scissors beats Paper, and Paper beats Rock.
- The game keeps track of the player's wins and losses.
- Players can view their scores at any time by pressing "v".
- Players can return to the main menu at any time by pressing "m".
- Players can exit the game at any time by pressing "0".

## Libraries Used

- **colorama**: A Python library for adding color and style to terminal output. It is used for styling text in the console interface.
- **random**: Python's standard library used for generating random numbers and selections.
- **sys**: Python's standard library used for interacting with the Python interpreter. It is used for exiting the game.
- **time**: Python's standard library used for time-related functions.
- **os**: Python's standard library used for interacting with the operating system. It is used for file I/O operations.
- **tkinter**: Python's standard GUI (Graphical User Interface) library. While this game is not built with a GUI, tkinter was initially imported but not used.

## How to Run

1. Ensure you have Python installed on your system.
2. Install the colorama library using the following command:

```bash
pip install colorama
```

3. Run the following command in your terminal to execute the game:

```bash
python rock_paper_scissors.py
```

4. Follow the instructions displayed in the terminal to play the game.

## Developer

- Developed by: wajihaadnan
