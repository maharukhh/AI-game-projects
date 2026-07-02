# A* Pathfinding Algorithm Visualization

A Python-based implementation of the A* pathfinding algorithm using Pygame to visualize the shortest path between two points in a grid.

## About This Project

This project demonstrates the A* search algorithm for finding the shortest path in a grid-based environment with obstacles. The visualization is done using Pygame.

It helps in understanding how pathfinding works in AI and game development.

## Features

* A* pathfinding algorithm implementation
* Grid-based environment
* Fixed obstacle layout
* Visualization using Pygame
* Shortest path highlighting
* Start and goal node representation

## Technologies Used

* Python
* Pygame
* Heapq (Priority Queue)

## Algorithm Used

A* Algorithm:

```text id="a1"
A* = g(n) + h(n)

g(n) = cost from start to current node
h(n) = heuristic (Manhattan distance)
```

## Heuristic Used

* Manhattan Distance:

  ```text
  |x1 - x2| + |y1 - y2|
  ```

## Project Structure

```text id="a2"
pathfinding-astar/
│
├── main.py              # Source Code
├── README.md            # Documentation
└── output/              # Output Screenshots
 
```

## Output

The program visualizes:

* Blue grid → Walkable nodes
* Black blocks → Obstacles
* Red circle → Start node
* Green circle → Goal + Path

Screenshots are saved in the `output/` folder.

## How to Run

```bash id="a3"
python main.py
```

## How It Works

1. Grid is initialized (10x10)
2. Obstacles are placed manually in code
3. A* algorithm searches shortest path
4. Priority queue selects best node
5. Path is reconstructed using parent mapping
6. Result is visualized using Pygame

## Limitations

* Fixed start and goal positions
* Fixed obstacles (no user input)
* Only Manhattan heuristic used
* No interactive controls
* No performance statistics

## Applications

* Game AI pathfinding
* Robotics navigation
* GPS routing systems
* AI simulation environments

## Future Improvements

* Add interactive grid editing
* Allow start/goal selection via mouse
* Add multiple heuristics
* Add performance metrics
* Add animation of search process
* Add real-time obstacle placement

## Author

Mahrukh

Robotics & Intelligent Systems Student passionate about Artificial Intelligence, Pathfinding Algorithms, and Game Development.
