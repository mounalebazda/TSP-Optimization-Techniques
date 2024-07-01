## Introduction

The Travelling Salesman Problem (TSP) is a well-known combinatorial optimization problem that aims to find the shortest possible route that visits a set of cities and returns to the origin city. This repository explores different techniques to solve the TSP, providing a comparative analysis of their performance.

## Implemented Techniques

### Branch and Bound
Branch and Bound is an exact method that systematically explores all possible solutions to find the optimal one. It uses bounds to prune the search space, making the process more efficient.

### Heuristics

#### Nearest Neighbour (NN)
The Nearest Neighbour heuristic constructs a tour by repeatedly visiting the nearest unvisited city.

#### 2-opt
The 2-opt heuristic iteratively improves a tour by reversing segments to reduce the total distance.

### Meta-Heuristics

#### Simulated Annealing (RS)
Simulated Annealing is a probabilistic technique that explores the solution space by allowing worse solutions with a decreasing probability, mimicking the annealing process in metallurgy.

#### Tabu Search (RT)
Tabu Search is an iterative improvement algorithm that uses a tabu list to avoid cycling back to previously visited solutions.

### Advanced Meta-Heuristics

#### Ant Colony Optimization (ACO)
Ant Colony Optimization is inspired by the foraging behavior of ants. It uses pheromone trails to guide the search towards promising regions of the solution space.

#### Genetic Algorithm (GA)
Genetic Algorithms mimic the process of natural selection. They use crossover and mutation operators to evolve a population of solutions.

## Results

Each notebook contains detailed results and analysis of the performance of the respective technique. Comparative analysis and visualizations are also provided.

