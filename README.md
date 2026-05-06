# Scikit-learn Tutorial

Original tutorial material from *Jake VanderPlas*

- email: <jakevdp@uw.edu>
- twitter: [@jakevdp](https://twitter.com/jakevdp)
- github: [jakevdp](http://github.com/jakevdp)

This repository contains notebooks and other files associated with the [Scikit-learn](http://scikit-learn.org) tutorial.
The notebooks have been updated by NeSI (http://github.com/nesi/sklearn_tutorial.git) to run with recent versions of Python and dependencies.

Recordings of the original workshop are available on Youtube:

- https://www.youtube.com/watch?v=L7R4HUQ-eQ0 (3 hours version)
- https://www.youtube.com/watch?v=HC0J_SPm9co (1.5 hours version)


## Installation Notes

To run the notebooks on your laptop, you will need to clone the repository:

```
git clone https://github.com/nesi/ml101_workshop.git
```

Note also that some of the code in these notebooks will not work outside the directory structure of this tutorial, so it is important to clone the full repository if possible.

Then, we recommend that you download and install [Miniforge](https://github.com/conda-forge/miniforge).
Once Miniforge is installed, navigate to your local copy of the repository and use the following command to create a Conda environment with all required packages:

```
cd ml101_workshop/
conda env create -f environment.lock.yml
```

Then activate your environment:

```
conda activate skl_tut
```

The tutorial material has been tested with the following package versions:

- Python version 3.12.7
- `numpy` version 2.4.4: [numpy.org](https://www.numpy.org)
- `scipy` version 1.17.1: [scipy.org](https://www.scipy.org)
- `matplotlib` version 3.10.9: [matplotlib.org](https://matplotlib.org)
- `scikit-learn` version 1.8.0: [scikit-learn.org](https://scikit-learn.org)
- `jupyterlab` version 4.5.7: [jupyterlab docs](https://jupyterlab.readthedocs.io)
- `ipywidgets` version 8.1.8: [ipywidgets docs](https://ipywidgets.readthedocs.io)
- `pandas` version 3.0.2: [pandas.pydata.org](https://pandas.pydata.org/)
- `pypdf` version 6.10.2: [pypdf docs](https://pypdf.readthedocs.io)


## Notebook Listing

Start `JupyterLab` using:

```
jupyter lab 
```

Then navigate the directory structure.
The notebooks are under the directory `notebooks`.
Click on `Index.ipynb` to get started.
