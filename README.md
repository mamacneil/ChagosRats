# Code for Graham *et al.* 
# *Seabirds fuel coral reef productivity and functioning in the absence of invasive rats*

This repository holds the entire code used for the Bayesian statistical analysis and plots presented in Graham *et al*'s manuscript *Seabirds fuel coral reef productivity and functioning in the absence of invasive rats*. This code is part of a manuscript in press.

All modelling and plots were produced in [Python 3](https://www.python.org/), via [Anaconda](https://www.anaconda.com/what-is-anaconda/), and the [PyMC3](http://docs.pymc.io/index.html) Bayesian modelling package. These must be installed to replicate our analysis.

If you would like to replicate our analysis, clone this repository and install [Jupyter](https://jupyter.org/), then proceed running the code in the associated Jupyter notebooks in this order:

	- 01_Chagos_d15N.ipynb
	- 02_Chagos_vonB.ipynb
	- 03_Chagos_fish_biomass.ipynb
	- 04_Chagos_grazing.ipynb
	- 05_Chagos_erosion.ipynb
	- 06_Chagos_plots.ipynb

This will reproduce the entire analysis from start to finish, re-estimating the various parameters etc from the original data. Note that new results will differ slightly from those in the paper due to new initial random starting values and the nature of Bayesian analysis. However, new results should be nearly identical.

Please contact Aaron MacNeil ([a.macneil@dal.ca](mailto:a.macneil@dal.ca)) for questions regarding the code or modelling.