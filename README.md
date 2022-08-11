# NUIG_BME_402_6101

This repository contains [Jupyter notebooks](https://jupyter.org/) for the module: _BME 403/6101 Computational Methods for Engineering Analysis_. The jupyter notebooks require [Octave](https://octave.org/index) (some use [Julia](https://julialang.org/) but this module uses MATLAB+Octave).

## 1. Install Octave
Download and install [Octave](https://octave.org/index) (an open source alternative to MATLAB).

## 2. Install Jupyter and the Octave kernel
The [Jupyter installation instructions](https://jupyter.org/install) refer to installation using the Python package management systems `pip` or `conda`, instructions for the former are reproduced below.

To get `pip` use (skip if pip is already installed):
```
python get-pip.py install
``` 
Next to get Jupyter use:
```
pip install notebook
```
Next add the [Octave kernel](https://pypi.org/project/octave-kernel/):
```
pip install octave_kernel
```

## Running the notebooks
If Octave, Python, and Jupyter are set-up, you can download the source files and run:
```
jupyter notebook
```

## Presenting the notebooks using `RISE`
To enable presenting the Jupyter notebooks as slides one needs to add the Jupyter slideshow extension [`RISE`](https://rise.readthedocs.io/en/stable/installation.html).

You can configure `RISE` using the notebook metadata JSON file, e.g. to enable the chalkboard use (see also: https://rise.readthedocs.io/en/stable/customize.html):
```
{
"rise": {
  "enable_chalkboard": true
}
```
