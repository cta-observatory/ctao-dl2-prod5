---
hide:
  - toc
---

# CTAO Monte Carlo Simulations - DL2 prod5

This site provides a simple overview of the dataset CTAO Monte Carlo Simulations at DL2 level: [https://zenodo.org/records/7298569](https://zenodo.org/records/7298569)

To get more information about the dataset, please visit the Zenodo page.

For up-to-date code examples, please visit the ctapipe documentation: [https://cta-observatory.github.io/ctapipe/](https://cta-observatory.github.io/ctapipe/).

## Installation

To run the notebooks on your computer, create a new conda environment and install the required packages:

```bash
conda env create -f environment.yml
conda activate ctaodl2
```

Then start Jupyter:

```bash
jupyter-lab
```

## Contents

- [Simulation info](simu_info.ipynb)
- [DL2 Parameters](dl2_params.ipynb)
- [Events Images](display_images.ipynb)
- [Reconstruction performances](dl2_performances.ipynb)
