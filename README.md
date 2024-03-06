# Snake AI Game

This repository contains a Python-based AI for playing the classic Snake game. The project utilizes the Pygame library for game development and a simple neural network for the AI agent, making decisions based on the game state.

## Features

- **Game Environment**: Implemented using Pygame, featuring a simple and intuitive interface.
- **AI Agent**: Uses a neural network to decide movements based on the current game state, aiming to maximize the score while avoiding collisions.
- **Customizable Parameters**: Easily adjustable parameters for learning rate, memory size, batch size, and more to fine-tune the AI's performance.

## Requirements

To run this project, you'll need:

- Python 3.x
- Pygame
- PyTorch
- NumPy

You can install the necessary libraries using pip:

pip install pygame torch numpy

## Usage

Clone the repository to your local machine and navigate to the cloned directory:

```bash
git clone https://github.com/pavan98765/SnakeAi.git
```

```bash
cd SnakeAi
```

To start the game and AI training, run:

```bash
python agent.py
```

## How It Works

The AI agent receives the game state as input, which includes the direction of the snake, the location of the food, and potential dangers. The agent then decides the next move to increase its score while avoiding death. The decision-making process is powered by a neural network trained on past game states and outcomes.

## Customization

You can adjust various parameters in `train.py` to experiment with the AI's learning process, such as:

- `MAX_MEMORY`
- `BATCH_SIZE`
- `LR` (Learning Rate)
- `self.epsilon` for exploration-exploitation trade-off

## Contributing

Contributions are welcome! If you have suggestions for improvements or bug fixes, feel free to open an issue or pull request.

```

```
