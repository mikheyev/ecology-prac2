# Practical 2 for Ecology (BIOL2131/BIOL6004 - Ecology - Sem 1 2019)

You can launch the interactive environment directly by clicking on this button [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/mikheyev/ecology-pracs/master), but...
## Before you click anything, consider installing everything onto your computer
It may take a while to build the virtual machine (~10 minutes), if no one has accessed the repository in a while, or it has changed. If you wish, you can install the Jupyter notebook environment, R and the other necessary packages on your computer. This will require you to be a bit IT-savvy, but can be done with a few commands. You can do this by installing the `conda` package manager (choose the Python 3.7 installer, most likely the 64-bit, for your operating system [here](https://conda.io/en/latest/miniconda.html)). You can then install all the necessary software by [downloading everything in this folder](https://github.com/mikheyev/ecology-prac2/archive/master.zip), decompressing it and running the following command `conda env create -f environment.yml` in your terminal. This sets up a virtual environment with all the software necessary to run the prac on your computer. You can then access this environment by typing `conda activate ecology-prac2` and then running the command `jupyter notebook`.
You can get more documentation about the conda package manager and environments [here](https://docs.conda.io/projects/conda/en/latest/user-guide/tasks/manage-environments.html). If all of this seems too complex, the link above should work.

Just make sure that you're using the latest version of the repository for turning in the final assignment (it will be the one set up by the day of the prac).
