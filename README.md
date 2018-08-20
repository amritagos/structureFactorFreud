# What this code does
These are a set of Python codes for calculating the structure factor (and 3-D RDF) from lammps trajectory files, using the package freud

# Dependencies 

The program requires the following dependencies:

* [Pipenv](https://pipenv.readthedocs.io/en/latest/) 
* [lammps](https://lammps.sandia.gov/doc/Manual.html)
* [PyLammps](https://lammps.sandia.gov/doc/Howto_pylammps.html)
* [Jupyter Notebooks](http://jupyter.org/install.html)

# Directory Structure
The top-level directory contains the following folders:
* lammpsFiles - This contains the lammps input files. Strictly speaking, only the data files are required to subsequent lammps trajectory files
* traj - This contains the lammps trajectory files to be processed

The top-level directory contains the Jupyter notebooks which can be run to calculate the RDF for a single step, RDF averaged over multiple steps, structure factor for a single step and multiple steps.
