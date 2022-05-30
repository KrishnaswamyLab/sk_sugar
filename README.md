# SUGAR
> Python version of [sugar][sugar]



## Install

`pip install sk-sugar`

# Setup

To get all the pagackes required, run the following command:

```bash
$ conda env create -f environment.yml
```
This will create a new conda environment sklab-sugar, which can be activated via:

```bash
$ conda activate sklab-sugar
```


## Add kernel to Jupyter Notebook

### automatic conda kernels

For greater detail see the official docs for nb_conda_kernels. In short, install nb_conda_kernels in the environment from which you launch JupyterLab / Jupyter Notebooks from (e.g. base) via:

```bash
$ conda install -n <notebook_env> nb_conda_kernels
```

to add a new or exist conda environment to Jupyter simply install ipykernel into that conda environment e.g.

```bash
$ conda install -n <python_env> ipykernel
```

### manual ipykernel

add to your Jupyter Notebook kernels via

```bash
$ python -m ipykernel install --user --name sklab-sugar
```

It can be removed via:

```bash
$ jupyter kernelspec uninstall sklab-sugar
```

list kernels found by Jupyter

kernels recognized by conda

```
$ python -m nb_conda_kernels list
```

check which kernels are discovered by Jupyter:
```bash
$ jupyter kernelspec list
```
