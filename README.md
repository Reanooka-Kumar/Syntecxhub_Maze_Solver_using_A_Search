# Syntecxhub_Maze_Solver_using_A*_Search

# 🗺️ A* Search Maze Solver

This project implements the powerful A* (A-star) pathfinding algorithm to efficiently find the shortest route between two points on a grid, navigating around obstacles (walls).

It serves as a comprehensive demonstration of graph search algorithms, heuristic function usage, and visual pathfinding.

## ✨ Features

* **Grid Representation:** Models the maze environment using a 2D array representing navigable paths, walls, a start point, and a goal.
* **A\* Pathfinding:** Core implementation of the A\* algorithm, ensuring the shortest path is found by optimizing the total cost function $f(n) = g(n) + h(n)$.
* **Heuristic Function:** Utilizes the **Manhattan Distance** heuristic for efficient search estimation.
* **Shortest Path Retrieval:** Reconstructs and returns the optimal path from the start to the goal.
* **Unreachable Case Handling:** Gracefully handles scenarios where a path to the goal does not exist.
* **Graphical Visualization:** Uses Matplotlib to render the final path on the grid clearly marking walls, the start, the goal, and the solution path. 

## 🛠️ Technology Stack

* **Language:** Python
* **Libraries:** `heapq` (for the Priority Queue), `matplotlib` (for visualization)

## 🚀 Getting Started

### Prerequisites

You need Python 3 installed. You will also need the Matplotlib library for the graphical visualization.

```bash
pip install matplotlib


## **💡 Algorithm Deep DiveThe**
A* algorithm works by evaluating nodes based on the following cost function:$$f(n) = g(n) + h(n)$$$g(n)$ (Cost from Start): The actual cost (number of steps) from the initial node to the current node $n$.$h(n)$ (Heuristic Cost): The estimated cost from the current node $n$ to the goal node. We use the Manhattan Distance for $h(n)$, which is the sum of the absolute differences of the coordinates.This approach ensures the algorithm is both efficient (thanks to the heuristic) and optimal (it always finds the shortest path).🧩 Maze Structure ExampleThe maze is represented as a 2D Python list where:0 represents a navigable Path1 represents an Obstacle / Wall

MAZE_1 = [
    [0, 0, 0, 0, 1, 0, 0, 0, 0, 0],
    [0, 1, 1, 0, 1, 0, 1, 1, 1, 0],
    # ... more rows ...
    [0, 0, 0, 0, 0, 1, 0, 0, 0, 0]
]


## **✍️ Author**
REANOOKA K
Gen AI and Data Science enthusiast
**GitHub:** https://github.com/Reanooka-Kumar
**Connect:** https://www.linkedin.com/in/reanooka-kumar-612a28314/
