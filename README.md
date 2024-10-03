# Optimizing Electric Grid Design Using Prim’s Algorithm for Minimum Spanning Tree (MST)

## Project Overview

This project implements **Prim’s Algorithm** to optimize the design of an electric grid or communication network by finding the Minimum Spanning Tree (MST). The algorithm is implemented in **C++** and uses a priority queue to efficiently find the minimum-cost connection between cities.

### Real-World Application

In infrastructure design, such as laying **electric grids** or **communication networks**, it's crucial to minimize the cost of connecting all cities (nodes) by selecting optimal routes (edges) that avoid cycles and reduce overall costs. This project models such problems using a graph where:
- **Nodes** represent cities.
- **Edges** represent the cost of laying cables or power lines between cities.

By applying **Prim's Algorithm**, we find the MST that ensures all cities are connected at the minimum possible cost.

---

## Project Structure

```bash
Prim-MST-Electric-Grid-Optimization/
├── README.md
├── src/
│   └── prim_mst.cpp          # C++ implementation of Prim's Algorithm
├── data/
│   └── example_input.txt      # Example graph input for testing the algorithm
├── images/
│   └── mst_visualization.png  # Optional visualization of the MST
