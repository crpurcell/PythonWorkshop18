# Jupyter Notebook Demonstration

In this Jupyter Notebook we will use Python to explore and analyse
some astronomical data. The techniques used here are (mostly) common
to all sorts of 3-D datasets, however, we will be using some astronomy
specific libraries to access astronomical data in FITS format.

## Installation

We will create a Python 3 anaconda environment to ensure that
everybody has the same modules and versions. Create the environment by
executing the following on the command line:
```
conda env create -f astroEnv.yml
```


## Data

You will need to download some astronomical data-cubes to complete
this exercise. Execute the following on the command line:
```
wget http://web.science.mq.edu.au/~cpurcell/public/downloads/dataHOPS.zip
```

Once everything is installed, activate the new conda environment and
start the Jupyter Notebook:

```
source activate astroEnv
jupyter-notebook
```








