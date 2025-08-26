## Peg Solitaire Game: 

[Peg Solitaire Repo](https://github.com/sigreipel/PegSolitaireGame)

Peg Solitaire Game is a Python-based implementation of the puzzle Peg Solitaire. The program simulates a board created in the `square.txt`, rules are defined in `Rules.txt`, and manages game progression and victory conditions in `EliminationGame.py`.

<ins>Features:</ins>

- Board Initialization and Configuration
- Reads and constructs the board layout from a text file (square.txt).
- Supports flexible board shapes or layouts through text-based configuration.

Game Rule Enforcement

- Encapsulates movement logic in Rules.py, ensuring that only valid peg jumps (over adjacent pegs into empty spaces) are allowed.
- Validates game state transitions—jump moves update board state correctly and enforce game rules.

Gameplay Management

- EliminationGame.py handles turn progression, move application, and detects game-over conditions (i.e., only one peg remains or no valid moves remain).
- Provides core logic for peg elimination and board updates.

<ins>TechStack:</ins>

Language: Python

Input: square.txt for board layout

Modules:

- Rules.py – movement validation
- EliminationGame.py – game state management
- square.txt – defines initial board setup

<ins>Future Improvements</ins>

- Implement a graphical interface (e.g., using Tkinter or Pygame) to make interaction more intuitive and engaging.
- Add move history and undo/redo functionality to enable exploration and backtracking.
- Integrate automatic solving algorithms, such as depth-first search or heuristic-driven methods, to allow users to request hints or complete the puzzle automatically.
- Extend board flexibility, including triangular or European variants, enabling comparative analysis of board types.
- Incorporate performance optimizations, such as memoization of board states or pruning techniques, to enhance solver efficiency.
