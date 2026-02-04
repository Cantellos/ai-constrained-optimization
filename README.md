# Artificial Intelligence & Constrained Optimization (IAOV)

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
![Python Version](https://img.shields.io/badge/python-3.8%2B-blue)

This repository contains a collection of exercises and projects developed for the **Artificial Intelligence and Constrained Optimization** course. The goal is to provide clean, documented, and efficient implementations of core AI search and optimization algorithms.

## 🚀 Key Features

The repository is organized into thematic modules:

* **State-Space Search:** Implementation of Informed and Uninformed search algorithms (A*, BFS, DFS, and Uniform Cost Search).
* **Constraint Satisfaction Problems (CSP):** Solvers for N-Queens, Map Coloring, and Sudoku using Forward Checking and Arc Consistency (AC-3).
* **Combinatorial Optimization:** Local search heuristics, Hill Climbing, and [add other algorithms like Genetic Algorithms if applicable].
* **Exam Lab Scenarios:** Solutions to past exam papers and complex problem-solving scenarios.

## 🛠️ Tech Stack

* **Language:** Python 3.x
* **Libraries:** `numpy`, `scipy`, `python-constraint` (modify according to your tools)
* **Environment:** Jupyter Notebooks / CLI Scripts

## 📥 Installation & Usage

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/Cantellos/IA-Ottimizzazione-Vincolata.git](https://github.com/Cantellos/IA-Ottimizzazione-Vincolata.git)
    ```

2.  **Install dependencies:**
    ```bash
    pip install -r requirements.txt
    ```

3.  **Run an example:**
    ```bash
    python src/search_example.py
    ```

## 📝 Project Structure
```text
├── src/                # Core algorithm implementations
├── notebooks/          # Interactive walkthroughs and tutorials
├── docs/               # Theoretical notes and exercise descriptions
└── tests/              # Unit tests for algorithm verification
