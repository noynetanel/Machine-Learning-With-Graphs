# Traversal-Based Positional Encodings for Graph Neural Networks

This repository contains the code and experiments for our project in the course **0368309001 – Machine Learning with Graphs** at **Tel Aviv University**.  

The project investigates traversal-based positional encodings for Graph Neural Networks (GNNs), with a focus on **Breadth-First Search (BFS) ranks**. We evaluate their effectiveness against baseline models and alternative positional encoding strategies on standard graph classification benchmarks.

## Repository Structure

For each dataset used in our experiments (**PROTEINS, NCI1, ENZYMES, REDDIT-BINARY, IMDB-BINARY, DD**), we created a dedicated folder.  
Each dataset folder contains:  
- **Jupyter notebooks** with the Kaggle runs  
- **Excel files** summarizing the results  

To make collaboration easier, we split the experiments for each dataset into three main notebooks:  
1. `baseline-bfs` – baseline model and BFS positional encoding  
2. `bfs-k-roots` – experiments with multiple BFS roots (k-roots)  
3. `learnable-layerwise-sinusoidal-bfs` – experiments with learnable, layerwise, and sinusoidal BFS encodings  

