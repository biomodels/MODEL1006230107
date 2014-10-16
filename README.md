# MODEL1006230107: Sneyd1995_CalciumWave_IP3diffusion

## Installation

Download this repository, and install with distutils

`python setup.py install`

Or, install using pip

`pip install git+https://github.com/biomodels/MODEL1006230107.git`

To install a specific version (in this example, from the 2014-09-16 BioModels release)

`pip install git+https://github.com/biomodels/MODEL1006230107.git@20140916`

## Usage

Importing the model package.

`import MODEL1006230107 as model`

Get the SBML string from the model

`print model.sbmlString`

If [python-libsbml](https://pypi.python.org/pypi/python-libsbml) bindings are
installed, the libsbml.SBMLDocument object is also accessible

`model.sbml`


# Model Notes


This a model from the article:  
**Intercellular calcium waves mediated by diffusion of inositol trisphosphate: a two-dimensional model.**   
Sneyd J, Wetton BT, Charles AC, Sanderson MJ. _Am J Physiol_ 1995 Jun;268(6 Pt
1):C1537-45 [7611375](http://www.ncbi.nlm.nih.gov/pubmed/7611375) ,  
**Abstract:**   
In response to mechanical stimulation of a single cell, airway epithelial
cells in culture exhibit a wave of increased intracellular free Ca2+
concentration that spreads from cell to cell over a limited distance through
the culture. We present a detailed analysis of the intercellular wave in a
two-dimensional sheet of cells. The model is based on the hypothesis that the
wave is the result of diffusion of inositol trisphosphate (IP3) from the
stimulated cell. The two-dimensional model agrees well with experimental data
and makes the following quantitative predictions: as the distance from the
stimulated cells increases, 1) the intercellular delay increases
exponentially, 2) the intracellular wave speed decreases exponentially, and 3)
the arrival time increases exponentially. Furthermore, 4) a proportion of the
cells at the periphery of the response will exhibit waves of decreased
amplitude, 5) the intercellular membrane permeability to IP3 must be
approximately 2 microns/s or greater, and 6) the ratio of the maximum
concentration of IP3 in the stimulated cell to the Km of the IP3 receptor
(with respect to IP3) must be approximately 300 or greater. These predictions
constitute a rigorous test of the hypothesis that the intercellular Ca2+ waves
are mediated by IP3 diffusion.

This model was taken from the [CellML
repository](http://www.cellml.org/models) and automatically converted to SBML.  
The original model was: [ **Sneyd J, Wetton BT, Charles AC, Sanderson MJ.
(1995) - version=1.0**
](http://models.cellml.org/exposure/88053fd5c8867b72ee23c1702097e377)  
The original CellML model was created by:  
**Wei Liu**   
wliu052@aucklanduni.ac.nz  
The University of Auckland  

This model originates from BioModels Database: A Database of Annotated
Published Models (http://www.ebi.ac.uk/biomodels/). It is copyright (c)
2005-2011 The BioModels.net Team.  
To the extent possible under law, all copyright and related or neighbouring
rights to this encoded model have been dedicated to the public domain
worldwide. Please refer to [CC0 Public Domain
Dedication](http://creativecommons.org/publicdomain/zero/1.0/) for more
information.

In summary, you are entitled to use this encoded model in absolutely any
manner you deem suitable, verbatim, or with modification, alone or embedded it
in a larger context, redistribute it, commercially or not, in a restricted way
or not..  
  
To cite BioModels Database, please use: [Li C, Donizelli M, Rodriguez N,
Dharuri H, Endler L, Chelliah V, Li L, He E, Henry A, Stefan MI, Snoep JL,
Hucka M, Le Novère N, Laibe C (2010) BioModels Database: An enhanced, curated
and annotated resource for published quantitative kinetic models. BMC Syst
Biol., 4:92.](http://www.ncbi.nlm.nih.gov/pubmed/20587024)


