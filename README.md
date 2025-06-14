# Applied-Reinforcement-Learning-MushroomRL
This repository contains a series of reinforcement learning assignments and experiments implemented using the MushroomRL framework. The projects focus on the development, training, and evaluation of various RL algorithms in simulated environments as part of academic coursework.



##Reinforcement Learning Library: 

MushroomRL: https://github.com/MushroomRL/mushroom-rl


# Assignment 1 - Stairway to Heaven
This assignment focuses on implementing and analyzing various RL algorithms to solve the "Stairway to Heaven" grid-world environment using the MushroomRL library.

## 🏗️ Environment
The "Stairway to Heaven" environment features:
- Agent that can move in 4 directions (up, down, left, right)
- Lava river that gives penalties when touched
- Button that builds a stairway to heaven (3% collapse probability)
- 5% action failure probability
- Rewards:
  - +1.0 for reaching heaven
  - -0.1 for hitting lava
  - -0.01 for other transitions

![Stairway to Heaven Environment Visualization](images/stairway_to_heaven.png)

## 🧠 Implemented Algorithms
1. **Dynamic Programming**:
   - Policy Iteration (PI)
   - Value Iteration (VI)
   - Modified Policy Iteration with initialization
   - Exact Policy Evaluation

2. **Model-Free Methods**:
   - First-Visit Monte Carlo
   - TD(n) Prediction
   - Q-Learning
   - SARSA
   - SARSA(λ)
