# VIC Observations

Fetching and visualising BOM observation data for Victoria, Australia


## Installing

A few dependencies are required to run the notebooks which can be installed using [pip](https://pypi.org/project/pip/).

It is recommended to use a conda environment/virtual environment for managing these depen


The visualisation require a library which is called [Cartopy](https://scitools.org.uk/cartopy/docs/latest/)
which isn't the easiest to install on Windows. The easiest way is to install the required dependencies via [conda](https://docs.conda.io/en/latest/miniconda.html).
Once that is installed, a new conda environment can be created with:

```
conda create --file=requirements.txt --channel=conda-forge --name=vic-obs
```

This step downloads and installs all the required dependencies and can take a few minutes,
but only needs to be performed once.
Once installed, the environment can be activated using:

```
conda activate vic-obs
```


### Pip

A new virtual environment can be created using:
```
python -m venv venv
source venv/bin/activate
```

This step downloads and installs all the required dependencies and can take a few minutes,
but only needs to be performed once.
Once installed, the environment can be activated using:

```
source venv/bin/activate
```



## Running Notebooks

Once installed and activated, a new notebook server can be started with:

```
jupyter notebook
```

This should open a new tab and go to the `notebooks/` directory to get started.