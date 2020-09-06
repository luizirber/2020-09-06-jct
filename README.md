# JCT

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/luizirber/2020-09-06-jct/latest?urlpath=lab/tree/index.ipynb)

## Setup

All processing and analysis scripts were performed using the conda environment specified in `environment.yml`.
To build and activate this environment run:

```bash
conda env create --force --file environment.yml

conda activate 2020-09-06-jct
```

After installing the conda environment,
you can also use `repo2docker` to create a container with all dependencies,
just like what is executed in `Binder`.
```bash
repo2docker .
```
