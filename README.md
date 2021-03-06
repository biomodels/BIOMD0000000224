# BIOMD0000000224: Meyer1991_CalciumSpike_ICC

## Installation

Download this repository, and install with distutils

`python setup.py install`

Or, install using pip

`pip install git+https://github.com/biomodels/BIOMD0000000224.git`

To install a specific version (in this example, from the 2014-09-16 BioModels release)

`pip install git+https://github.com/biomodels/BIOMD0000000224.git@20140916`

## Usage

Importing the model package.

`import BIOMD0000000224 as model`

Get the SBML string from the model

`print model.sbmlString`

If [python-libsbml](https://pypi.python.org/pypi/python-libsbml) bindings are
installed, the libsbml.SBMLDocument object is also accessible

`model.sbml`


# Model Notes


This a model from the article:  
** Calcium spiking. **   
Meyer T, Stryer L _Annu Rev Biophys Biophys Chem_1991:20:153-74
[1867714](http://www.ncbi.nlm.nih.gov/pubmed/1867714),  
**Abstract:**   
No Abstract Available

The IP3-Ca2+ Crosscoupling Model (ICC) is reviewed by Meyer and Stryer in
1991, originally from Meyer and Stryer, 1988. PMID -
[2455890](http://www.ncbi.nlm.nih.gov/pubmed/2455890) Parameters refer to
figures 5 and 6 of the article which were reproduced by using Copasi 4.5
(Build 30). Species CaI and IP3 are buffered to 1% and 50% percent,
respectively.

This model originates from BioModels Database: A Database of Annotated
Published Models. It is copyright (c) 2005-2009 The BioModels Team.  
For more information see the [terms of
use](http://www.ebi.ac.uk/biomodels/legal.html).  
To cite BioModels Database, please use [Le Novère N., Bornstein B., Broicher
A., Courtot M., Donizelli M., Dharuri H., Li L., Sauro H., Schilstra M.,
Shapiro B., Snoep J.L., Hucka M. (2006) BioModels Database: A Free,
Centralized Database of Curated, Published, Quantitative Kinetic Models of
Biochemical and Cellular Systems Nucleic Acids Res., 34: D689-D691.](http://ww
w.pubmedcentral.nih.gov/articlerender.fcgi?tool=pubmed&pubmedid=16381960)


