# A* Pathfinding Visualizer Game

An interactive pathfinding visualizer built with Python and Pygame. The project demonstrates how the A* search algorithm finds the shortest path between a start point and an end point while avoiding obstacles.

## Project Overview

This project allows users to create a custom grid, place a start node, end node, and walls, then visualize how the A* algorithm explores nodes and finds the shortest path in real time.

## Features

* 30x30 interactive grid
* Left click to place start point, end point, and walls
* Right click to erase nodes
* Press Space to run the A* algorithm
* Press C to clear and reset the grid
* Real-time visualization of explored nodes and final path

## Algorithm Used

The project uses the A* search algorithm.

A* calculates the best path using:

F(n) = G(n) + H(n)

Where:

* G(n) = actual distance from the start node
* H(n) = estimated distance to the end node
* F(n) = total estimated cost

The heuristic used in this project is Manhattan Distance:

H(n) = |x1 - x2| + |y1 - y2|

## Color Mapping

* Orange = Start Node
* Turquoise = End Node
* Black = Wall / Obstacle
* Green = Open Set
* Red = Closed Set
* Purple = Final Shortest Path
* White = Empty Node

## Technologies Used

* Python
* Pygame
* PriorityQueue

## How to Run

1. Install Python.
2. Install Pygame:

```bash
pip install pygame
```

3. Run the project:

```bash
python main.py
```

## Project Documents

The report and presentation are included in the `docs` folder.

## Author

Muhammad Shah Noor Ullah
BS Electronics and Computing
COMSATS University Islamabad
