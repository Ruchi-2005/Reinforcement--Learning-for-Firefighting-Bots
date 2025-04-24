# Reinforcement--Learning-for-Firefighting-Bots
# INTRODUCTION

In real-life emergency situations like forest or urban fires, effective and timely coordination among firefighting teams is essential to reduce damage and protect lives. These environments are highly unpredictable, often characterized by limited resources (such as water), physical barriers, and the need for smart coordination among responders. To explore solutions to these challenges, this project presents a simulation that models firefighting on a grid, where multiple autonomous agents (representing firefighters) work together using Artificial Intelligence (AI) techniques to locate and extinguish fires.

The goal of this simulation is to replicate the complexity of real-world firefighting by incorporating reinforcement learning (Q-learning), pathfinding (A* algorithm), and communication between agents to support teamwork. The simulation focuses on decentralized decision-making, efficient use of resources, and strategic movement. It provides a platform to investigate how AI can improve firefighting efforts by enabling intelligent collaboration among agents in fast-changing, resource-limited environments.

# ALGORITHM USED
1.	Independent Q-Learning (IQL)
2.	A* Pathfinding

# PACKAGES USED
1.	Numpy         >=1.19 
2.	Pygame        >=2.0.
3.	Random       >=3.7.0
4.	PIL (Pillow) >=8.0

# Objectives
Simulate a realistic firefighting scenario using AI agents.
Use reinforcement learning (Q-learning) for training autonomous agents.
Implement A* for optimal pathfinding across the grid.
Enable agent collaboration via a water-passing chain mechanism.
Demonstrate decentralized decision-making, resource sharing, and adaptive behavior in high-risk environments.

# Simulation Features
🔥 Fires can spread to nearby cells.

💧 Water sources are limited, requiring agents to refill.

🤝 Agents can pass water to teammates in need.

📍 10x10 grid environment with obstacles and fire zones.

🧠 Intelligent agents trained using reinforcement learning.




