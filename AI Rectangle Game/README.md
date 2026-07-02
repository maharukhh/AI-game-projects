# AI Rectangle Game

A simple 2D arcade-style game built using Python and Pygame where the player must avoid obstacles by jumping.

## About This Project

This is a beginner-level Pygame project that demonstrates basic game development concepts such as movement, jumping mechanics, collision detection, and game loops.

## Features

* Simple jump mechanics
* Moving obstacle
* Collision detection
* Game over system
* Basic Pygame window rendering

## Technologies Used

* Python
* Pygame

## Game Controls

* Space: Jump
* Close Window: Exit Game

## Project Structure

```text id="rct001"
rectangle-game/
│
├── main.py              # Source Code
├── README.md            # Documentation
└── output/              # Game Screenshots
    ├── output1.png
```

## Output

The game runs in a Pygame window where:

* Green rectangle = Player
* Black rectangle = Obstacle
* Game ends on collision

Screenshots are stored in the `output/` folder.

## How to Run

```bash id="runrct"
python main.py
```

## How It Works

1. Player rectangle stays on ground
2. Press space to jump
3. Obstacle moves from right to left
4. If collision occurs, game ends
5. If no collision, game continues

## Limitations

* Only one obstacle
* No scoring system
* No levels or difficulty increase
* No restart option
* No sound or UI elements

## Future Improvements

* Add scoring system
* Add multiple obstacles
* Add difficulty levels
* Add restart button
* Add sound effects
* Add animations
* Add leaderboard system

## Author

Mahrukh

Robotics & Intelligent Systems Student passionate about Artificial Intelligence, Game Development, and interactive Python projects.
