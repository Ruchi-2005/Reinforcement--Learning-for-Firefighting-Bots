# Reinforcement--Learning-for-Firefighting-Bots
# INTRODUCTION

This project is a Python simulation that replicates a real-life firefighting scenario using artificial intelligence. It showcases how a group of agents (representing firefighters) can collaborate to detect, manage, and extinguish fires on a grid-based environment. The simulation integrates Q-learning for strategic decision-making, the A* algorithm for efficient pathfinding, and a collaborative chain system that allows agents to pass water to one another.
Set on a 10x10 grid, the agents navigate the area to identify fires, collect water from designated sources, and support fellow agents by transferring water when needed. Fires can spread to neighboring tiles, increasing the challenge and emphasizing the need for effective teamwork among the agents.

# PYTHON PACKAGES

1.	numpy
Used for efficient array handling and mathematical operations.
Helps represent and manipulate the grid used in pathfinding.

2.	pygame
Handles 2D graphics, animations, user inputs, and game loop control.
Used to visualize the grid, fire animation, and pathfinding in real-time.

3.random
Generates random numbers and choices.
Used to randomize fire spread and starting positions.

4.PIL (Pillow)
Supports image manipulation and animation.
Used to resize and display animated GIFs for fire effects.

5.io, os
Provides tools for file and system-level operations.
Used for managing file paths and loading resources.

6.heapq
Implements an efficient priority queue.
Used to optimize node selection in the A* algorithm.


