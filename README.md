# Epidemic Models Simulation on Small-World Graphs

This repository contains Python code to simulate various epidemic models (SI, SIR, SIS, SIRS) on small-world graphs generated using the Watts-Strogatz model. The simulations explore how diseases spread through networks, considering different centrality measures.

## Introduction

Understanding the dynamics of disease spread is crucial for public health interventions. Network models provide valuable insights into how diseases propagate through populations. This project investigates epidemic models on small-world graphs, focusing on nodes with high centrality measures.

## Features

- Simulations of SI, SIR, SIS, and SIRS epidemic models
- Visualization of epidemic spread based on different centrality measures
- Modular code structure for easy experimentation and extension
- Utilizes NetworkX for graph manipulation and Matplotlib for visualization

## Usage

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/epidemic-models.git
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the simulations:
   ```bash
   python epidemic_simulation.py
   ```

4. View the simulation results in the generated plots.

## Requirements

- Python 3.x
- NetworkX
- Matplotlib
