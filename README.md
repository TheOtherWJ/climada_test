# Climada Test Project

This repository contains a Jupyter notebook I wrote in experimenting with [Climada](https://climada.ethz.ch/climada/) and instructions on how to create the same virtual environment I did to run the code (climada_test.ipynb).

Climada is an open-source software framework that allows you to model climate (economic/financial) risk of a variety of hazards for exposed assets and populations. I've not explored its functionality too far yet, but I got as far as projecting economic damages of river-floods in the UK in the future given a certain climate scenario. It is possible to define custom 'exposures' (e.g., an office or factory), in order to estimate potential damages of climate change. 

See the community-maintained coumentation, as well as links to tutorials [here](https://climada-python.readthedocs.io/en/stable/index.html).

Because I wanted to calculate the impact of river flooding, I had to install the [Climada Petals](https://github.com/CLIMADA-project/climada_petals) package, as well as the [Core](https://github.com/CLIMADA-project/climada_python) package. This meant I followed the [advanced instructions](https://climada-python.readthedocs.io/en/stable/guide/install.html#advanced-instructions).

To install Climada in the same way I did (and so be able to run my code), you can simply follow the [advanced instructions](https://climada-python.readthedocs.io/en/stable/guide/install.html#advanced-instructions), which involves cloning the github repositories and installing the python packages from the repositories themselves, rather than via pip or conda-forge, for example. The instructions recommend creating your virtual environment with Mamba, but I found that Conda (I used miniconda) to work just fine.
