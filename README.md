# Notebooks for Cylc

This repository contains Jupyter Notebooks for [Cylc](https://cylc.github.io/cylc/), a workflow engine.

The notebooks here were largely inspired and based on the notebooks written by [Nicolas Fauchereau](https://github.com/nicolasfauchereau/Python-for-data-analysis-and-visualisation).

## System requirements

The notebooks were developed and tested with [Continuum Anaconda](https://www.continuum.io/).

## Running

cylc requires Python 2 to run, so you need to tell Jupyter Notebook that you will need a Python 2 kernel.

```
conda create -n py27 python=2.7
source activate py27
conda install notebook ipykernel
ipython kernel install --user
```

Then you are ready to run the notebook.

```
jupyter notebook --ip=127.0.0.1 --port=8888
```

That should open a new browser window in the project folder. Click on the notebooks folder, and start learning more about cylc.
