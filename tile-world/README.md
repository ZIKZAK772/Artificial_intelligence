# Tile World Problem Solver using Genetic Network Programming

This project implements a Genetic Network Programming (GNP) approach to solve the Tile World problem. The Tile World problem involves arranging a 3x3 grid of tiles numbered from 1 to 8 (with one empty space represented by 0) to match a goal state from an initial random state. The goal is to reach the target state by moving the tiles.

## Problem Definition

### Initial State:
3 6 1
4 8 2
7 0 5

### Goal State:
1 2 3
4 5 6
7 8 0
## Approach

Genetic Network Programming (GNP) is used to find the sequence of moves that transforms the initial state into the goal state. The main steps of the GNP approach are:

1. **Initialization**: Generate an initial population of random individuals (sequences of moves).
2. **Evaluation**: Calculate the fitness of each individual based on how close they are to the goal state.
3. **Selection**: Select individuals to be parents for the next generation based on their fitness.
4. **Crossover**: Combine pairs of parents to create new individuals.
5. **Mutation**: Randomly alter some individuals to maintain genetic diversity.
6. **Iteration**: Repeat the evaluation, selection, crossover, and mutation steps for a fixed number of generations or until a solution is found.

## Installation

Ensure you have Python installed. Clone this repository to your local machine:

```bash
git clone https://github.com/yourusername/tile-world-gnp.git
cd tile-world-gnp

python main.py

Solution found in generation: 8
Solution:
1 2 3
4 5 6
7 8 0

