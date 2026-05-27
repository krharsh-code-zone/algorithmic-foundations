# ML & AI Algorithms from Scratch

## Overview
This repository is a growing collection of core machine learning and artificial intelligence algorithms built entirely from the ground up. 

The primary goal of this project is to translate raw mathematical formulas and algorithmic mechanics into working code without relying on high-level abstractions or black-box APIs (like `scikit-learn`). Implementations heavily utilize `numpy` for vectorized mathematical operations, custom distance metrics, and efficient matrix manipulations.

## Repository Structure
This repository is organized by algorithmic family. Each directory contains its own detailed `README.md` with specific documentation, mathematical context, and execution instructions for the models within.

```text
ml-algorithms-from-scratch/
├── README.md                  # This file
├── data/                      # Shared sample datasets (using relative paths)
├── clustering/                # Unsupervised clustering algorithms
│   ├── README.md
│   ├── k_mean++.ipynb
│   └── dbscan_learning.ipynb
└── future_implementations/    # (e.g., neural_networks, embeddings, etc.)
