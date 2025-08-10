# SEG DASCore Tutorial

A DASCore tutorial for CTEMPs 2025 workshop 

This repository provides a gentle introduction to DASCore, a Python library for distributed fiber optic sensing. The main first three jupyter notebooks are very similar to the [SEG 2024 tutorial](https://github.com/DASDAE/seg_tutorial/) with some updates, and the data exploratory analysis and processing in the 04_application jupyter notebook introduces new workflows. After completing the tutorial users should be able to:

1. Use DASCore to index, query, and chunk a directory of DAS files.

2. Create visualizations of DAS Patches.
   
3. Perform filtering to improve signal to noise ratio of seismic events.
   
4. Calculate time-based statistics on rolling windows of continuous data.

The introductory slides can be found [here](https://dasdae.github.io/presentations/ctepms_2024/ctemps_2024.html).

You will also find four notebooks in this repo containing examples and exercises.

*A DASCore version >= 0.1.9 is required.*

# Installation

Each of the notebooks has a "launch in collab" button you can use so you don't need to setup anything. However, if you wish to do this tutorial with a local installation of DASCore you can use the following section. 

## Local installation

To install DASCore, you can use pip:

```bash
pip install "dascore"
```

or conda/mamba (while also creating a virtual environment)

```bash
conda create -n dc_env dascore
```

or

```bash
mamba create -n dc_env dascore
```

Next, make sure jupyter notebook/lab is installed in your current environment then you are ready to open the notebooks.

```bash
jupyter
```

See the [DASCore installation documentation](https://dascore.org/#installation) for more details.
