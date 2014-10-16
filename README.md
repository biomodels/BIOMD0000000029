# BIOMD0000000029: model_0000001

## Installation

Download this repository, and install with distutils

`python setup.py install`

Or, install using pip

`pip install git+https://github.com/biomodels/BIOMD0000000029.git`

To install a specific version (in this example, from the 2014-09-16 BioModels release)

`pip install git+https://github.com/biomodels/BIOMD0000000029.git@20140916`

## Usage

Importing the model package.

`import BIOMD0000000029 as model`

Get the SBML string from the model

`print model.sbmlString`

If [python-libsbml](https://pypi.python.org/pypi/python-libsbml) bindings are
installed, the libsbml.SBMLDocument object is also accessible

`model.sbml`


# Model Notes


The model corresponds to the schema 3 of Markevich et al 2004, as described in
the figure 2 and the supplementary table S3, and modelled using Michaelis-
Menten like kinetics. Phosphorylations follow distributive random kinetics,
while dephosphorylations follow an ordered mechanism.

This model originates from BioModels Database: A Database of Annotated
Published Models. It is copyright (c) 2005-2007 The BioModels Team.  
For more information see the [terms of
use](http://www.ebi.ac.uk/biomodels/legal.html) .


