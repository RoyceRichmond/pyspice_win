# pyspice_win
installation on windows of the pyspice library for ngspice simulation

# installation of miniconda
For Windows the best alternative is to use Miniconda, this creates a virtual environment and avoids any version conflict, download miniconda, install it, and then open the Anaconda prompt terminal

# create new environment and install pyspice
Once you are on anaconda prompt terminal enter the following instructions

```
conda create --name ngspice python=3.9
conda activate ngspice
conda install -c conda-forge pyspice
```
this code has the following impact
1. Create a new virtual environment named "ngspice" with the latest version of python 3.9
1. activate the virtual environment (enter into this environment to make modifycations)
1. get PySpice on Anaconda

this is about it, this will act as a new installation of python, any new libraries for python should be installed through the Anaconda prompt terminal and activating the environment

An example of libraries installation (with the command needed for the installation) can be seen next

```
conda activate ngspice
pip install tqdm engineering-notation
```
for reference for a small library for Skywater130 https://github.com/ral298/skywater-pdk-libs-sky130_fd_pr

