[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/mlund/SI-multiscale-antibodies/HEAD)
[![CC BY 4.0][cc-by-shield]][cc-by]
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.10478576.svg)](https://doi.org/10.5281/zenodo.10478576)

[cc-by]: http://creativecommons.org/licenses/by/4.0/
[cc-by-shield]: https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg

# Electronic Notebook: A multiscale numerical approach to study monoclonal antibodies in solution

This deposition contains simulation data and electronic notebooks to reproduce results in the 
scientific paper _A multiscale numerical approach to study monoclonal antibodies in solution_.

## Layout

- `assets` Graphics
- `experiment` Experimental SAXS data
- `simulations` Metropolis-Hastings Monte Carlo setup and analysis

## Requirements

To run the Notebooks online, click on the _Launch Binder_ badge above. Alternatively, to run on your own computer,
install Python using _e.g._ [Miniforge](https://github.com/conda-forge/miniforge) or [Anaconda](https://docs.conda.io)
and make sure all required packages are loaded by issuing the following terminal commands

``` bash
conda env create -f environment.yml
source activate my_environment
jupyter-lab
```
