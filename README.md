# Snake Game AI

Snake Game            |  Plotted Results
:-------------------------:|:-------------------------:
![Snake Game Screenshot](https://github.com/user-attachments/assets/e999b42c-54c9-4336-8e4b-8a64b2930c64)  |  ![Plotted Results](https://github.com/user-attachments/assets/256f2924-e225-4c09-bec4-88031f2fe9c6)

> An AI-powered snake game using PyTorch to train a neural network to play the game.

## Overview

This project implements an AI agent that learns to play the classic Snake game using deep reinforcement learning. The agent is trained using a neural network to maximize the score by avoiding obstacles and consuming food.

## Features

- **Deep Q-Learning**: The AI uses a deep Q-network to predict the best moves.
- **Neural Network Architecture**: The model is built using PyTorch, with fully connected layers.
- **Training and Evaluation**: The agent's performance improves over time as it learns from its actions.

## Installation

To run this project locally, you will need Python and the following dependencies:

- Python 3.7
- PyTorch
- NumPy
- Matplotlib (for plotting results)
- Pygame (for game visuals)
- IPython (for plotting)

Install the required packages using pip:

```bash
pip install torch numpy matplotlib pygame ipython
```

## Usage
Simple run the agent file to start the training and gameplay
```bash
python agent.py
```

## Video Demo
Watch the AI play Snake

https://github.com/user-attachments/assets/33a40276-2d0d-4505-90f2-0f6bad5b2282

## Contributing
Contributions are welcome! Please submit a pull request or open an issue for any changes or suggestions.

## Acknowledgements
The game is built using the Pygame library.
AI training based on deep Q-learning techniques.
This was made with help from a free YouTube course from FreeCodeCamp
