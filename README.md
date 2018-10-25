# Data Analysis with Python

A short workshop of examples working with

- numpy
- pandas
- matplotlib

by @kayleanelson and @brevans for the [Yale Center for Research Computing](https://research.computing.yale.edu/training/ycrc-bootcamps/ycrc-bootcamp-data-analysis-python)

## Setup

To recreate the environment used to generate these notebooks, go get [Anaconda Python](https://www.anaconda.com/download) if you haven't already installed it. Then, clone or download this repo and run:
```
bash make_env.sh
```
Then you can activate the environment with
```
source activate DAP
```

## Slides
To generate slides for any of the notebooks, activate the `DAP` environment, then run 
```
jupyter nbconvert [].ipynb --to slides --post serve
```

Replacing `[]` with `intro`, `numpy`, `pandas`, or `matplotlib`.
