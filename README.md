markdown
# 🐍 Snake Game AI using Deep Q-Learning (DQN)

This project implements a reinforcement learning agent that learns to play the classic **Snake Game** using a **Deep Q-Network (DQN)**. The agent is trained to maximize its score by learning optimal movement strategies through trial and error.

## 🎯 Project Overview

- Built a Snake game environment using **Pygame**
- Designed and trained a **Deep Q-Network** using **PyTorch**
- Implemented **experience replay**, **epsilon-greedy exploration**, and **reward shaping**
- Visualized training progress with real-time score plots

## 🧠 Technologies Used

- Python
- PyTorch
- Pygame
- NumPy
- Matplotlib

## 🚀 How to Run

1. **Clone the repository**:
   ```bash
   git clone https://github.com/PriyankaMalisetty97/-Snake-Game-Intelligence-using-Deep-Q-Learning-DQN-.git
   cd -Snake-Game-Intelligence-using-Deep-Q-Learning-DQN-
2.Install dependencies:
   pip install pygame torch matplotlib numpy
3.Train the agent:
python main.py
This will launch the Snake game and begin training the AI agent. A real-time plot of scores will be displayed.

🧩 Project Structure
File	Description
main.py	---Main training loop and agent logic
model.py ---Neural network and Q-learning trainer
snake_game.py ---	Game environment built with Pygame
helper.py---	Utility functions for plotting and memory
model/ ---	Stores trained model checkpoints (model.pth)
🏆 Key Features
State Representation: 11-dimensional vector capturing snake direction, food location, and collision threats

Actions: [Straight, Right, Left] relative to current direction

Rewards:
+10 for eating food
-10 for dying
Small penalty for each step to encourage efficiency

Training Enhancements:
Experience Replay
Epsilon-Greedy Strategy
Real-time performance visualization
