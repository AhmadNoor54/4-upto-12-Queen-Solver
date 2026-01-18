# N-Queens CSP & A* Visualizer

A Python **Tkinter-based GUI application** that solves and visualizes the **N-Queens problem** using two Artificial Intelligence approaches:

- **Constraint Satisfaction Problem (CSP)** with backtracking  
- **A* Search Algorithm** using conflict-based heuristics  

The application allows users to define the board size and initial queen positions, then visually compares both algorithms **step-by-step**, along with performance metrics such as iterations and runtime.

---

## Algorithms Implemented

### 1. Constraint Satisfaction Problem (CSP)
- Uses **backtracking**
- Respects user-provided initial positions
- Places queens column by column
- Checks safety using row and diagonal constraints

### 2. A* Search
- State represented as a list of queen row positions per column
- Heuristic: **number of conflicting queen pairs**
- Explores neighboring states by moving queens within columns
- Stops when heuristic reaches zero (solution found)

---

## Requirements
- Python **3.8+**
- No external libraries required (uses standard library only)

---

## Usage

### Run the Application
```bash
python main.py
---
```
**Example:**
N = 8
Initial Positions = 0 4 7 5 2 6 1 3

⭐ If you find this project useful, consider giving it a star on GitHub!
