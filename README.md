# GridWorld: DP-based Reinforcement Learning

This repository contains my implementation of fundamental Dynamic Programming (DP) algorithms for solving Markov Decision Processes (MDP). The project demonstrates how an agent learns to navigate a grid, avoid traps, and reach a target using Bellman equations.



###  Algorithms Implemented
I’ve implemented and compared several core Reinforcement Learning approaches:
* **Policy Iteration**: A complete cycle of iterative policy evaluation and improvement
* **Value Iteration**: A direct method focusing on finding the optimal value function
* **Modified Policy Iteration (MPI)**: An efficient hybrid that balances computation time and convergence speed

###  The Environment
The **GridWorld** setup is fully customizable, allowing the definition of:
* **Walls**: Obstacles that the agent cannot pass through
* **Pitfalls**: Dangerous cells with negative rewards
* **Goal**: A terminal state with a high reward

###  Key Insights & Results
Through various experiments in the Jupyter Notebook, I analyzed:
* **Gamma ($\gamma$) Impact**: How the discount factor changes agent behavior — from "short-sighted" immediate gains to long-term strategic planning
* **Convergence Speed**: A comparison of the number of iterations (sweeps) required for each algorithm to converge under different thresholds ($\theta$)
* **Visualization**: State-value functions are visualized via heatmaps, and optimal strategies are displayed using direction arrows (Policy Maps)



###  Tech Stack
* **Python 3.10+**
* **NumPy**
* **Matplotlib**
* **Dataclasses & Typing**
