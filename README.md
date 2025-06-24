# ♟️ Chess Game with AI

A **pure Python chess game** built using **PyGame**, offering:

- 🎮 Local **PvP** and **AI** (Minimax + Alpha-Beta) support  
- 🖱️ Intuitive mouse-based GUI with drag-and-drop  
- 💬 Move commentary for invalid moves, checks, and more  
- ♟️ Full chess logic: castling, en passant, pawn promotion, and checkmate  

> 🔸 AI uses piece-square tables from the [Chess Programming Wiki](https://www.chessprogramming.org/PeSTO%27s_Evaluation_Function)


---

## 🚀 Getting Started

### A. Run via Python (recommended)
```bash
git clone https://github.com/OmarAhmedHaiduq/Chess-game-with-AI.git
cd Chess-game-with-AI
pip install pygame
python Main.py
```
#### Download Executable (no Python needed)

Download [Chess.exe]() under Assets

If blocked, click More Info → Run Anyway

##### 🗂️ Project Structure

| File            | Description                                    |
| --------------- | ---------------------------------------------- |
| `Main.py`       | Initializes game loop and handles user input   |
| `GUI.py`        | Draws board, buttons, and displays drag & drop |
| `Controller.py` | Handles move logic, game rules, and input      |
| `Engine.py`     | Minimax AI with alpha-beta pruning             |
| `Package.py`    | Packaging script for creating a `.exe` build   |

###### ✅ Requirements
Python 3.12+

PyGame: Install with pip install pygame
