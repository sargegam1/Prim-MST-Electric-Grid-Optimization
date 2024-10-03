# Prim's Algorithm for Electric Grid Optimization

## Project Overview

This project implements **Prim’s Algorithm** to optimize the design of an electric grid or communication network by finding the Minimum Spanning Tree (MST). The algorithm is implemented in C++ and is optimized using a priority queue to efficiently find the minimum-cost connection between cities.

The project uses a graph where nodes represent cities and edges represent the cost of laying cables or transmission lines. The goal is to connect all cities with the minimum possible cost, without forming cycles.

## Project Structure

```bash
Prim-MST-Electric-Grid-Optimization/
├── README.md
├── src/
│   └── prim_mst.cpp          # C++ implementation of Prim's Algorithm
├── images/
│   └── mst_visualization.png  # MST visualization (optional)
└── data/
    └── example_input.txt      # Input data for testing (optional)
