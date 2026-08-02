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

### 5. Dijkstra Pathfinding Visualization
Visualization of Dijkstra's algorithm finding the shortest path in a grid, with walls placed interactively and the search animated cell by cell.
* Algorithm: Dijkstra's Shortest Path
* Concepts: Priority queues, graph traversal, shortest-path search

### 6. Snake Game with AI
A classic Snake game where an AI autopilot uses Breadth-First Search to route the snake to the food while avoiding its own body, falling back to a flood-fill safety check when no path exists.
* Algorithm: BFS pathfinding with flood-fill fallback
* Concepts: Grid search, self-avoidance, real-time replanning

### 7. Racing Game with AI Opponent
A top-down racing game where an AI-controlled car races the player around an oval track by steering toward waypoints and adjusting speed through turns.
* Algorithm: Waypoint-following steering with turn-based speed control
* Concepts: Vector math, steering behaviors, lap/race state tracking

### 8. Tower Defense Game AI
A tower defense game where enemies use BFS to pathfind through a maze to the base, automatically rerouting when towers block their path, while towers auto-target the nearest enemy in range.
* Algorithm: BFS pathfinding (enemies) + nearest-target selection (towers)
* Concepts: Dynamic replanning, wave spawning, real-time targeting

### 9. Reinforcement Learning Game Agent
A tabular Q-learning agent that learns to navigate a grid world from start to goal while avoiding traps, purely through trial-and-error reward signals with no hardcoded path.
* Algorithm: Q-Learning (tabular, epsilon-greedy exploration)
* Concepts: Reward shaping, exploration vs. exploitation, learned policies

### 10. 3D Game Simulation (basic)
A minimal 3D engine built from scratch (no 3D library) that renders wireframe cubes with perspective projection and a flyable first-person camera.
* Algorithm: Manual 3D-to-2D perspective projection and camera-space transforms
* Concepts: 3D vector math, rotation matrices, projection, first-person camera control

## Upcoming Projects
This section will grow as new projects are added:
* More additions coming soon
## Technologies Used
* Python
* Pygame
* NumPy
* Matplotlib
* Tkinter

## Installation
Clone the repository:
```
git clone https://github.com/maharukhh/game-ai-projects.git
cd game-ai-projects
```

## Project Structure
```
game-ai-projects/
│
├── tic-tac-toe-ai/
├── rectangle-game/
├── pathfinding-astar/
├── Rock-Paper-Scissors AI that learns opponent patterns/
├── Dijkstra Pathfinding Visualization/
├── Snake Game with AI/
├── Racing Game with AI Opponent/
├── Tower Defense Game AI/
├── Reinforcement Learning Game Agent/
├── 3D Game Simulation (basic)/
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
* Dijkstra's Shortest Path
* BFS Pathfinding
* Steering Behaviors
* Q-Learning (Reinforcement Learning)
* 3D Projection & Camera Transforms

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
* Expand reinforcement learning agents to more complex environments
* Implement multiplayer support
* Expand algorithm visualizations

## Author
Mahrukh
Robotics & Intelligent Systems Student passionate about Artificial Intelligence, Game Development, and intelligent systems.
---
This repository will continue to evolve as more AI and game development projects are added.
