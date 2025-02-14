# 🐤 AI Flappy Bird

An AI-powered Flappy Bird game that learns to play using **NEAT (NeuroEvolution of Augmenting Topologies)**. The AI evolves over multiple generations to improve its gameplay.

## Features
- Uses **NEAT-Python** for training a neural network.
- Implements **pygame** for game visuals.
- AI learns from scratch and improves over time.
- Visualizes neural network connections.

## Installation
### Prerequisites
Ensure you have **Python 3.7+** installed.

### Clone the Repository
```sh
git clone https://github.com/your-username/AI-Flappy-Bird.git
cd AI-Flappy-Bird
```

### Install Dependencies
```sh
pip install -r requirements.txt
```

## Running the AI
To start training the AI, run:
```sh
python flappy_bird.py
```
The AI will begin playing and improving over generations.

## Configuration
The **config-feedforward.txt** file controls how the AI evolves. You can modify parameters like population size, activation functions, and mutation rates.

## How It Works
1. The AI starts with random birds (agents) that attempt to play the game.
2. Each bird has a neural network that takes input from the game environment.
3. Birds receive a **fitness score** based on how long they survive.
4. Using **genetic algorithms**, the best-performing birds evolve into better versions.
5. Over multiple generations, the AI learns optimal strategies to navigate obstacles.

## Visualizing AI Progress
You can visualize AI performance by running:
```sh
python visualize.py
```
This generates charts showing fitness evolution and neural network structures.

## Dependencies
- `pygame`
- `numpy`
- `neat-python`
- `matplotlib`
- `graphviz`

## Contributing
Feel free to open issues and contribute improvements!

## License
This project is licensed under the MIT License.

