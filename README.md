# Game-Playing-AI---DQN-Agent-for-CartPole

This project implements a basic Deep Q-Network (DQN) agent using Keras and Gymnasium to play the CartPole-v1 environment.
It demonstrates the core ideas behind reinforcement learning and game-playing AI.

📄 Project Structure

File	Description
app.ipynb	Main notebook containing the random agent and DQN agent code.
README.md	This instruction file.
🚀 How to Run
Install dependencies (if not already installed):


pip install gymnasium tensorflow keras numpy
Open app.ipynb in Jupyter Notebook, Google Colab, or any notebook environment.

Run all cells:

First, the Random Agent will play CartPole randomly.

Then, the DQN Agent will train and improve over episodes.

🧠 Key Concepts Used
Random Agent: Selects random actions without learning.

Deep Q-Network (DQN) Agent:

Uses a neural network to approximate Q-values.

Learns from past experiences (experience replay).

Updates exploration-exploitation balance using epsilon decay.

Fixed Issues for New Gym Versions:

env.reset() returns (observation, info)

env.step() returns (observation, reward, terminated, truncated, info)

📈 Example Training Output
During training, you will see outputs like:


DQN Agent - Episode 1/100, Total Reward: 15.0
DQN Agent - Episode 2/100, Total Reward: 22.0
...
DQN Agent - Episode 100/100, Total Reward: 200.0
The total reward usually increases as the agent learns.

📚 References
DeepMind's DQN Paper

OpenAI Gymnasium Documentation

Keras Documentation
