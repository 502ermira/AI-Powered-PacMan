# Smart PacMan Route Finder

This repository contains a project focusing on comparing different pathfinding algorithms using a custom implementation of Pac-Man. The Pac-Man game, written in Python 3, utilizes non-standard libraries PIL (Python Imaging Library) and Pygame. Pathfinding algorithms are employed to navigate Ghosts towards the Pac-Man sprite, with each ghost representing the use of a different search algorithm. This is a Pac-Man game implemented in Python using the Pygame library. The project simulates the classic Pac-Man game with functionalities for grid initialization, traversable cell coloring, collision detection, and pathfinding for ghost characters.

## Installation

To run this program, ensure that Pygame and PIL are installed on your machine:

- Use the following pip commands to install the required libraries:
    ```
    pip install pygame
    pip install PIL
    ```
- For additional information on installing Pygame, refer to the [Pygame Getting Started Guide](https://www.pygame.org/wiki/GettingStarted).

## Usage

- This game was primarily created to test different pathfinding algorithms.
- The main objective was to demonstrate that incomplete real-time pathfinding algorithms can perform efficiently and achieve the same degree of accuracy as complete algorithms when properly tuned to a finite state-space.
- The algorithms implemented in this project include:
  - Breadth-First Search
  - A*
  - Context Dependent Subgoaling A*

## Notes

- The Pac-Man game is a simplified version and does not include all features found in the original game.
- Feel free to experiment with different algorithms or modify the game to suit your needs.
- Contributions are welcome! If you have suggestions or improvements, please submit a pull request.
