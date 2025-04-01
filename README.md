# 📊 Simplex Solver in MATLAB

This project implements a two-phase **Simplex Method** in MATLAB for solving Linear Programming problems with support for test cases and real-world production scenarios.

---

## 🚀 Features

- Two-phase Simplex (feasibility + optimization)
- Handles:
  - Infeasible, unbounded, degenerate LPs
  - Slack/surplus/artificial variables
- Built-in test cases + user input mode
- Production planning use-case (inventory-based)

---

## 🧪 Modes

| Mode | Description              |
|------|--------------------------|
| 0    | Infeasible Problem       |
| 1    | Feasible LP              |
| 2    | Degeneracy               |
| 3    | Unbounded LP             |
| 7    | Production Optimization  |
| 8    | Custom User Input        |

---

## 🛠 Usage

1. Open `Simplex1.m` in MATLAB  
2. Run:
   ```matlab
   >> Simplex1
   ```
3. Select a mode (0–8) when prompted

---

## 📦 Files

- `Simplex1.m` — Main solver script  
- `inventory5.db` — Sample data (for production mode)

---

## 📬 Contact

Connect on [LinkedIn](https://www.linkedin.com/in/prannoy-kathiresan) for queries or collab!
