# n-puzzle-astar

> N-Puzzle Solver with A* Search

![Language](https://img.shields.io/github/languages/top/J1u2a3n8/n-puzzle-astar)
![License](https://img.shields.io/github/license/J1u2a3n8/n-puzzle-astar)
![Last Commit](https://img.shields.io/github/last-commit/J1u2a3n8/n-puzzle-astar)
![Stars](https://img.shields.io/github/stars/J1u2a3n8/n-puzzle-astar?style=social)
![Issues](https://img.shields.io/github/issues/J1u2a3n8/n-puzzle-astar)

## Description

Optimal N-Puzzle (8-puzzle, 15-puzzle) solver using A* search with Manhattan distance and linear conflict heuristics. Includes visualization of search process and performance comparison with other algorithms.

## Architecture

Search: Priority Queue (Open Set) → Heuristic (Manhattan + Linear Conflict) → Goal Test → Path Reconstruction

## Quick Start

### Prerequisites

Python 3.10+, pip/poetry, Jupyter Lab

### Installation

```bash
# Clone
git clone https://github.com/J1u2a3n8/n-puzzle-astar.git
cd n-puzzle-astar

pip install -r requirements.txt
# jupyter lab
```

### Usage

```bash
jupyter notebook notebooks/n-puzzle-astar.ipynb
```

## Testing

```bash
pytest tests/
```

## Project Structure

```
n-puzzle-astar/
├── src/              # Main source code
├── tests/            # Unit/integration tests
├── docs/             # Documentation
├── .github/          # CI/CD workflows
└── README.md
```

## Tech Stack

Python, NumPy, heapq, Matplotlib, Jupyter

## License

This project is licensed under the **MIT License** - see [LICENSE](LICENSE) for details.

## Author

**J1u2a3n8** - [GitHub](https://github.com/J1u2a3n8) - [LinkedIn](https://linkedin.com/in/juanluiscanedo)

---

⭐ If you found this project useful, give it a star!
