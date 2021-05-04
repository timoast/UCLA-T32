# Single-Cell Analysis Workshop

This repository contains code for the June 2021 single-cell analysis
workshop held at UCLA.

## Getting started

The easiest way to get started is to install miniconda if you haven't
already: https://docs.conda.io/en/latest/miniconda.html

Next, clone this repository:

```sh
git clone git@github.com:timoast/UCLA-T32.git
cd UCLA-T32/
```

Create and activate a new conda environment using the environment file
in this repository:

```sh
conda env create -f environment.yaml
conda activate t32
```

Next launch R and install the required packages:

```r
IRkernel::installspec()
install.packages("Seurat")
```
