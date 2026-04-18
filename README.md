# 🧬 Genetic Algorithm: Simulation & TSP Solver

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Artificial Intelligence](https://img.shields.io/badge/AI-Evolutionary_Algorithms-FF6F00?style=for-the-badge)

This repository contains Python implementations of a Genetic Algorithm (GA), a metaheuristic inspired by natural selection. This project was developed as an Open Ended Lab for the Artificial Intelligence course. 

It demonstrates how biologically inspired operators—such as selection, crossover, and mutation—can be utilized to generate high-quality optimization solutions. 

## 📂 Project Structure

The project is divided into two distinct parts to demonstrate both the fundamental mechanics and a practical application of the algorithm:

### 1. Basic GA Simulation (`ga_basic_simulation.py`)
A simple, foundational example designed to simulate and understand how the genetic algorithm works under the hood.
* **Objective:** Finds the maximum value of the function f(x) = x² within a bounded range (0 to 31).
* **Operators Used:** Roulette wheel selection, bitwise crossover, and bitwise mutation.

### 2. Computing Problem Application (`ga_tsp_solver.py`)
Applies the coded genetic algorithm to solve a complex computing problem: **The Traveling Salesperson Problem (TSP)**. 
* **Objective:** Finds the shortest possible route that visits a set of cities and returns to the origin city.
* **Operators Used:** Roulette wheel selection, Order Crossover (OX) to prevent duplicate city visits, and swap mutation.

## 🚀 How to Run

This project uses Python's standard libraries, meaning no external dependencies or virtual environments are required.

**1. Clone the repository:**
```bash
git clone [https://github.com/yourusername/genetic-algorithm-oel.git](https://github.com/yourusername/genetic-algorithm-oel.git)
cd genetic-algorithm-oel
2. Run the Basic Simulation:

Bash
python ga_basic_simulation.py
3. Run the Traveling Salesperson Solver:

Bash
python ga_tsp_solver.py