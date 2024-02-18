# Edge Collapse On Randon Clique Complex
##Python code for simulating the edge collapse procedure on Erdos-Renyi clique complex

This repository contains Python code to simulate the edge collapse process on random simplicial complexes, as described in the paper "On Edge Collapse of Random Simplicial Complexes" submitted to SoCG'24. Edge collapse is a method to reduce the size of a simplicial complex while preserving its homotopy (and hence homology). Running this edge collpase recursively on a simplicial effectively reduces the size of the complex reducing the complex to its core. The code estimate size the core of random simplicial complexes to support theretical results obtained in the concerened paper.



## Overview

The simulation code consists of three main files:

1. `randomedgecollapse-3.ipynb`: This Jupyter Notebook file contains the code to run the edge collapse process recursively on random simplicial complexes. It generates data regarding the core of the complex by simulating the process on multiple random complexes.

2. `edgecol_output_data-3.csv`: This CSV file stores the output data generated by the `randomedgecollapse-3.ipynb` notebook. It contains information about the core of the random simplicial complexes.

3. [Add description of the third file once it's created]



soumikdt/Edge-Collapse-On-Randon-Clique-Complex/
│
├── randomedgecollapse-3.ipynb
├── edgecol_output_data-3.csv
├── simulation_output/        # Folder for output data of the first code
│   ├── simulation_output_1.csv
│   ├── simulation_output_2.csv
│   └── ...
├── visualization_script.py   # Third code for visualization (if created)
├── visualization_output/     # Folder for visualization output files
│   ├── visualization_output_1.png
│   ├── visualization_output_2.png
│   └── ...
├── README.md
└── LICENSE    


## Usage

To run the edge collapse simulation:

1. Open the `randomedgecollapse-3.ipynb` notebook in a Jupyter environment.
2. Follow the instructions within the notebook to execute the code and simulate the edge collapse process.
3. The generated data will be saved to the `edgecol_output_data-3.csv` file.

To visualize the data:

[Add instructions once the third file is created]










