# Artificial Intelligence - ECE NTUA 2022-23

This repository contains Jupyter notebooks from the Artificial Intelligence course labs at ECE NTUA for the academic year 2022-23. The labs explore various AI techniques and algorithms, with practical implementations and simulations.

## Contributors

- [Karam Konstantinos](https://github.com/KostasKram)
- [Kolios Apostolos](https://github.com/apostolos-k)

## Labs Overview

### Lab 1 - Maze Generator & Pathfinding

In this lab, we implemented an N x N maze generator using the Randomized Depth-First Search algorithm (Iterative Implementation). The generated mazes are then used to test various pathfinding algorithms:

- **Dijkstra's Algorithm**
- **Best-First Search**
- **A\* Algorithm**

For the A\* Algorithm, we utilized different heuristic functions such as Manhattan and Euclidean distances to find the shortest path efficiently.

Additionally, we created a simulation of a chase inside the maze between a player and a ghost, implementing the Alpha-Beta pruning algorithm for the ghost's decision-making process.

### Lab 2 - Movie Recommender System in Prolog

In this lab, we developed a movie recommender system using Prolog, integrated within a Jupyter notebook via the `pyswip` library. The system offers two types of recommendations:

- **Content-Based Recommendations:** Suggests movies based on characteristics such as genre, year, actors, etc.
- **Collaborative Filtering:** Recommends movies based on user ratings of other movies, providing a similarity score to indicate how likely a movie is to be enjoyed by the user.

The recommendation system includes a scale to measure the likelihood of a user liking a particular movie, offering a more personalized suggestion.

## Reports

All lab reports and explanations are provided in Greek.
