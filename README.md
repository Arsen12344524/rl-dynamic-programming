# Reinforcement Learning: Dynamic Programming in GridWorld

This project implements fundamental Dynamic Programming (DP) algorithms to solve Markov Decision Processes (MDP). The goal is to find the optimal policy for an agent in a custom GridWorld environment.

##  Implemented Algorithms
- **Policy Evaluation**: Iterative calculation of the state-value function $V^\pi$.
- **Policy Iteration**: Finding the optimal policy by alternating between evaluation and improvement.
- **Value Iteration**: Directly computing the optimal value function to derive the policy.
- **Modified Policy Iteration (MPI)**: A more efficient hybrid approach.

##  Environment: GridWorld
The agent operates in a 2D grid with:
- **Obstacles (Walls)**: Non-passable cells.
- **Pitfalls**: Negative rewards (traps).
- **Goal**: The target state with a high positive reward.

##  Key Insights
- Analyzed the impact of the discount factor ($\gamma$) on agent behavior.
- Compared convergence speeds (number of iterations/sweeps) between Policy and Value Iteration.
- Visualized the results using Value Heatmaps and Policy Arrows.

##  Tech Stack
- Python 3
- NumPy
- Dataclasses & Typing
- Matplotlib (for visualization)
