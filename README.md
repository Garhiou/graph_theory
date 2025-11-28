# Graph Theory

Small collection of Jupyter notebooks where I implement basic graph structures and classic graph theory problems in Python.

This repository is mainly a learning project: I use it to explore graphs, implement well-known algorithms from scratch, and experiment with different problem types.

---

## Contents

Currently the repository contains the following notebooks:

- **`graphs.ipynb`**  
  Basic experiments with graphs:
  - Representing graphs (e.g. adjacency list / adjacency matrix)
  - Adding/removing nodes and edges
  - Simple queries on graphs (neighbors, degree, etc.)

- **`bipartite_check.ipynb`**  
  Checks whether a graph is bipartite, typically by:
  - Trying to 2-color the graph using BFS/DFS
  - Detecting conflicts (odd cycles) where the graph cannot be bipartite

- **`3clique_graph.ipynb`**  
  Experiments with cliques, in particular 3-cliques (triangles):
  - Searching for all 3-node cliques in a given graph
  - Understanding the relationship between edges, triangles and graph density

- **`hamilton_problem.ipynb`**  
  Playing with Hamiltonian paths and cycles:
  - Searching for a Hamiltonian path/cycle
  - Using backtracking / brute force to explore all possibilities on small graphs


More notebooks and algorithms may be added over time.

---

## Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/Garhiou/graph_theory.git
cd graph_theory
