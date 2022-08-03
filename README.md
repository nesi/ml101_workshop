# Scikit-learn Tutorial

Original tutorial material from *Jake VanderPlas*

- email: <jakevdp@uw.edu>
- twitter: [@jakevdp](https://twitter.com/jakevdp)
- github: [jakevdp](http://github.com/jakevdp)

This repository contains notebooks and other files associated with the
[Scikit-learn](http://scikit-learn.org) tutorial. The notebooks have been 
updated by NeSI (http://github.com/nesi/sklearn_tutorial.git) to run with recent
versions of Python and dependencies.


## Installation Notes

Read [NESI.md](NESI.md) to find out how to run the notebooks on NeSI.
All the packages required by the tutorial are already installed on NeSI's [jupyter hub](https://jupyter.nesi.org.nz/).

If you prefer to run on your own computer then we recommend that you download and install [miniconda](http://conda.pydata.org/miniconda.html).
Once `miniconda` is installed, the following command will install all required packages in your Python environment.
```
conda create -n skl_tut -c conda-forge python=3.8 numpy scipy matplotlib=3.2.2 scikit-learn=0.22.1 pillow jupyterlab ipywidgets pandas
```
Then activate your environment:
```
conda activate skl_tut
```

The tutorial material has been tested on NeSI with the following package versions:
- Python version 3.10.5
- `numpy` version 1.22.4: https://www.numpy.org
- `scipy` version 1.8.1: https://www.scipy.org
- `matplotlib` version 3.5.2: https://matplotlib.org
- `scikit-learn` version 1.1.1: https://scikit-learn.org
- `jupyterlab` version 3.4.3: https://jupyterlab.readthedocs.io
- `ipywidgets` version 7.7.0: https://ipywidgets.readthedocs.io
- `pandas` version 1.4.2: https://pandas.pydata.org/


## Downloading the Tutorial Materials

We have already installed all the notebooks on NeSI's [jupyter hub](https://jupyter.nesi.org.nz/). However,
if you prefer to run on your laptop, you will need to clone the repository:
```
git clone https://github.com/nesi/sklearn_tutorial.git
```

Note also that some of the code in these notebooks will not work outside the
directory structure of this tutorial, so it is important to clone the full
repository if possible.


## Notebook Listing

If you have followed the installation instructions to run on your laptop, start `JupyterLab`:
```
jupyter lab 
```
Then navigate the directory structure. The notebooks are under the directory `notebooks`.
Click on `Index.ipynb` to get started.
