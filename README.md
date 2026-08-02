# AI Game Projects

A scalable collection of Python-based game development and artificial intelligence projects. This repository is continuously updated with new games, AI algorithms, and interactive simulations.

## About This Repository
This repository includes game development and AI-focused projects built using Python. It is designed as a learning and experimentation space for implementing classic and advanced AI algorithms in games.

The projects demonstrate concepts such as:
* Game Development
* Artificial Intelligence
* Pathfinding Algorithms
* Decision Making Systems
* Simulation and Visualization
* Game State Management
New projects will be added regularly as development continues.

## Projects Included (Current)

### 1. Tic-Tac-Toe with AI
An AI-based Tic-Tac-Toe game where the computer plays optimally using the Minimax algorithm.
* Algorithm: Minimax with Alpha-Beta Pruning
* AI Strength: Optimal play
* Concepts: Game trees, decision making

### 2. Rectangle Game
A simple interactive game built using Pygame with movement, collision detection, and scoring.
* Framework: Pygame
* Concepts: Game loops, collisions, scoring system

### 3. A* Pathfinding Visualization
Visualization of the A* algorithm for finding the shortest path in a grid with obstacles.
* Algorithm: A* Search
* Concepts: Heuristics, graph traversal, optimization

### 4. Rock-Paper-Scissors AI that learns opponent patterns
An AI opponent for Rock-Paper-Scissors that learns the player's habits over time and counters them, instead of playing randomly. Includes both a terminal version and a Tkinter GUI version.
* Algorithm: Markov-chain-style pattern prediction (context of recent moves → predicted next move)
* AI Strength: Improves over time against players with real patterns; converges to ~33% win rate against fully random play
* Concepts: Sequence/pattern learning, adaptive decision making, simple state tracking

## Upcoming Projects
This section will grow as new projects are added:
* Dijkstra Pathfinding Visualization
* Snake Game with AI
* Racing Game with AI Opponent
* Tower Defense Game AI
* Reinforcement Learning Game Agent
* 3D Game Simulation (basic)

## Technologies Used
* Python
* Pygame
* NumPy
* Matplotlib
* Tkinter

## Installation
Clone the repository:
```bash id="c1m8ra"
git clone https://github.com/maharukhh/game-ai-projects.git
cd game-ai-projects
```
Install dependencies:
```bash id="n9k2sd"
pip install -r requirements.txt
```

## Running a Project
Each project can be run independently:
```bash id="p4x8lm"
cd project-folder
python main.py
```

## Project Structure
```text id="q8m1zn"
game-ai-projects/
│
├── tic-tac-toe-ai/
├── rectangle-game/
├── pathfinding-astar/
├── Rock-Paper-Scissors AI that learns opponent patterns/
├── upcoming-projects/
├── requirements.txt
└── README.md
```
Each project typically includes:
* main.py (entry point)
* core game logic
* AI implementation (if applicable)
* assets (if required)

## Key Concepts Covered
* Minimax Algorithm
* Alpha-Beta Pruning
* A* Pathfinding
* Game Loops
* Collision Detection
* Heuristic Search
* State Management
* Markov-chain Pattern Prediction

## Learning Outcomes
This repository helps in understanding:
* How AI behaves in games
* How pathfinding algorithms work
* Game development fundamentals
* Algorithm optimization techniques
* Building interactive Python applications
* How simple models can learn and adapt to opponent behavior

## Roadmap
Future development direction:
* Add more AI-based games
* Improve graphics and animations
* Add reinforcement learning agents
* Implement multiplayer support
* Expand algorithm visualizations

## Author

Mahrukh

Robotics & Intelligent Systems Student passionate about Artificial Intelligence, Game Development, and intelligent systems.
---
This repository will continue to evolve as more AI and game development projects are added.
