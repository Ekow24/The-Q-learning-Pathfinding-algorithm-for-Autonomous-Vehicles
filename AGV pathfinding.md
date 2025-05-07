![Reinforcement Learning](./RL.png)

# AGV Pathfinding using Q-Learning

This repository presents a reinforcement learning-based approach for optimizing pathfinding in **Autonomous Guided Vehicles (AGVs)** within dynamic, obstacle-filled factory environments. By using the **Q-learning algorithm**, AGVs learn to navigate efficiently through trial-and-error, adapting to their surroundings and improving over time.

## 🧠 Project Overview

AGVs are crucial in modern industrial automation, performing tasks like material handling and transport. Traditional pathfinding methods (e.g., A*, Dijkstra) work well in static settings but struggle with dynamic changes in the environment.

This project explores the application of **Q-learning**, an off-policy reinforcement learning algorithm, to enable AGVs to:
- Learn optimal navigation paths
- Avoid dynamic obstacles
- Return to base after completing tasks

## 📚 Key Features

- **Grid-based Environment (10x10):** Dynamic grid with reward penalties for obstacles and incentives for shortest paths.
- **Q-learning Implementation:** Utilizes states, actions, rewards, discount factors, and a Q-table to learn optimal policies.
- **Exploration vs. Exploitation:** Uses epsilon-greedy strategy to balance learning new paths vs. exploiting known good ones.
- **Return-to-Base Capability:** Trains the agent not only to reach the goal but also to return to the base station autonomously.
- **Performance Metrics:** Visualizes episode rewards, steps taken, and learning efficiency over 300 episodes.

## 🔧 Technologies Used

- Python 
- NumPy (for matrix operations)
- Matplotlib (for plotting performance graphs)
- Reinforcement Learning Concepts (Q-learning, Markov Decision Processes)

## 📈 Results

- Improved pathfinding efficiency over time (shorter routes, higher rewards)
- Successful navigation to goal and return to base station
- Learned policy generalizes well to new start positions
- Observed better performance with lower exploration rates (epsilon = 0)


