# Exercises_ML

This repo contains the coding exercises for the "Machine Learning" course at the Technical University of Munich (TUM).

## Virtual Environment Setup

First of all, we need to setup a virtual environment in order to install the packages contained in the file `requirements.txt`. We can decide between *virtualenv* and *Anaconda*.

### Anaconda Setup

Download and install miniconda (minimal setup with less start up libraries) or conda (full install but larger file size) from [here](https://www.anaconda.com/products/distribution#Downloads). Create an environment using the terminal command:

`conda create --name ML_env python=3.10`

Next activate the environment using the command:

`conda activate ML_env`

### Virtualenv Setup

Run in the terminal the command: `pip install virtualenv`

Then, create the environment by running: `python3.10 -m venv ML_env`.

Next activate the environment using the command (MACOS):

`source ML_env/bin/activate` 

After that we are ready to install the packages in our virtual environment running: `pip install -r requirements.txt`

