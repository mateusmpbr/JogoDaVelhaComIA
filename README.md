# 4x4 Tic-Tac-Toe with AI (Minimax + Alpha-Beta pruning)

This project implements a 4x4 variant of Tic-Tac-Toe (Jogo da Velha) with an AI opponent powered by the Minimax algorithm and Alpha-Beta pruning.

**Features:**

- 4x4 board variant of Tic-Tac-Toe
- Single-player mode against an AI using Minimax and Alpha-Beta pruning
- Simple command-line interface (run and follow on-screen prompts)

**Requirements:**

- Python 3.8 or newer

**Quick start:**

1. Open a terminal in the project directory.
2. Run:

```bash
python3 jogo.py
```

Follow the on-screen instructions to play. The program will prompt for moves and display the board state.

**About the AI:**
The AI uses the Minimax search algorithm with Alpha-Beta pruning to evaluate possible moves and choose the best play. Alpha-Beta pruning reduces the number of nodes the algorithm evaluates, improving performance while preserving optimal play under the chosen evaluation and search depth.

**Possible improvements:**

- Add a GUI for improved usability
- Expose AI configuration (search depth, time limits) via command-line flags
- Implement different difficulty levels by limiting search depth or using heuristics
- Add multiplayer over network or save/load game support

**Files:**

- `jogo.py` — main program (game loop and AI integration)

**License:**
See the LICENSE file for licensing information.

Enjoy playing!
