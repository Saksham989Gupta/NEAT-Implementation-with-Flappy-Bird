# NEAT-Implementation-with-Flappy-Bird

This project is an AI agent that plays the Flappy Bird game and continuously evolves to become unbeatable using the NEAT (NeuroEvolution of Augmenting Topologies) algorithm. The AI starts with random behavior but gradually learns and improves by evolving neural networks to master the game.

# Features
**Automated Gameplay:** The AI automatically plays the game, making decisions based on neural networks.<br>
**Evolutionary Learning:** The AI continuously evolves by improving its neural network through generations using NEAT.<br>
**Visualization:** The project includes visual feedback to show how the AI is performing in the game.

# How It Works
The AI starts with a population of birds, each controlled by a neural network.<br>
Each bird plays the game independently, trying to pass through pipes without hitting them.<br>
Birds that perform well (i.e., survive longer and pass more pipes) are allowed to reproduce, with their neural networks evolving and mutating.<br>
Over generations, the AI learns to master the game by optimizing its ability to avoid obstacles<br>

# Technologies Used
**Programming Language:** Python<br>
**Game Library:** Pygame<br>
**AI Library:** NEAT-Python
