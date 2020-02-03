# 2-Day Workshop - Introduction to Data Science in Python

Materials for the Paris-Saclay Center for Data Science python workshop

Data science is gaining attention impacting many scientific fields and
applications. Data science encompasses a large number of topics such as data
mining, data wrangling, data visualisation, pattern recognition, or machine
learning.

This workshop intends to give an introduction to some of these topics using
Python and the PyData ecosystem. It is not a course on deep learning.

You can run the notebooks in a binder:
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/lesteve/2020-sed-intro-datascience/master)

## Program

### Day 1 -  Data wrangling, exploration, and visualisation

**Goal:** introduce the PyData ecosystem to manipulate, explore, and visualize data.

* Introduction to the basics of numpy, pandas, matplotlib, and Dask.

### Day 2 - Machine learning

**Goal:** introduce the basics of machine learning using the  scikit-learn library.

* Get familiar with general principles of machine learning;
* Use these principles by using the scikit-learn library on some toy and real-world data examples.

## Getting started

The course uses Python 3 and some data analysis packages such as Numpy, Pandas,
scikit-learn, matplotlib, and Dask.

### Install Miniconda

**Only necessary if you don't have conda installed**:
- download the Miniconda installer for your OS [here](https://docs.conda.io/en/latest/miniconda.html)
- run the installer following the instructions
  [here](https://conda.io/projects/conda/en/latest/user-guide/install/index.html#regular-installation)
  depending on your OS.

### Create conda environment

```
# Clone this repo
git clone https://github.com/lesteve/2020-sed-intro-datascience
cd 2020-sed-introdatascience
# Create a conda environement with the required packages for this tutorial:
conda env create -f environment.yml
# Activate your conda environment
conda activate intro-datascience
```

### Install/check of required packages

We **strongly recommend** you to open and execute the script located at the
root of this repository to make sure you have the necessary packages installed:

```
python check_env.py
```
