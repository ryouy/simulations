# Simulations

Python simulations that run in Google Colab.

## 2D Infection Simulation

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ryouy/simulations/blob/main/infection_simulation.ipynb)

[Notebook](infection_simulation.ipynb) · [Open in Google Colab](https://colab.research.google.com/github/ryouy/simulations/blob/main/infection_simulation.ipynb)

30 particles move within a 2D square. Initially one particle is red (infected); contact spreads infection to white particles. Run the notebook top to bottom to view the animation and export MP4, GIF, CSV, PNG, and JSON outputs.

To push outputs to this repository, set `GITHUB_TOKEN` in **Colab → Secrets**, allow notebook access, and run the final cell. The token needs **Contents: Read and write** access to `ryouy/simulations`. Never commit the token.

Generated outputs are stored in `outputs/` when uploaded.
