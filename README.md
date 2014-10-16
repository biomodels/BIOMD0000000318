# BIOMD0000000318: yao08

## Installation

Download this repository, and install with distutils

`python setup.py install`

Or, install using pip

`pip install git+https://github.com/biomodels/BIOMD0000000318.git`

To install a specific version (in this example, from the 2014-09-16 BioModels release)

`pip install git+https://github.com/biomodels/BIOMD0000000318.git@20140916`

## Usage

Importing the model package.

`import BIOMD0000000318 as model`

Get the SBML string from the model

`print model.sbmlString`

If [python-libsbml](https://pypi.python.org/pypi/python-libsbml) bindings are
installed, the libsbml.SBMLDocument object is also accessible

`model.sbml`


# Model Notes


This is the model described in the article:  
**A bistable Rb-E2F switch underlies the restriction point**   
Guang Yao, Tae Jun Lee, Seiichi Mori, Joseph R. Nevins, Lingchong You, _Nat
Cell Biol_ 2008 10:476-482; PMID:
[18364697](http://www.ncbi.nlm.nih.gov/pubmed/18364697) ; DOI:
[10.1038/ncb1711](http://dx.doi.org/10.1038/ncb1711) .

Abstract:  
The restriction point (R-point) marks the critical event when a mammalian cell
commits to proliferation and becomes independent of growth stimulation. It is
fundamental for normal differentiation and tissue homeostasis, and seems to be
dysregulated in virtually all cancers. Although the R-point has been linked to
various activities involved in the regulation of G1-S transition of the
mammalian cell cycle, the underlying mechanism remains unclear. Using single-
cell measurements, we show here that the Rb-E2F pathway functions as a
bistable switch to convert graded serum inputs into all-or-none E2F responses.
Once turned ON by sufficient serum stimulation, E2F can memorize and maintain
this ON state independently of continuous serum stimulation. We further show
that, at critical concentrations and duration of serum stimulation, bistable
E2F activation correlates directly with the ability of a cell to traverse the
R-point.

This model reproduces the serum-pulse stimulation-protocol in Figure 3(b).

  

To the extent possible under law, all copyright and related or neighbouring
rights to this encoded model have been dedicated to the public domain
worldwide. Please refer to [CC0 Public Domain
Dedication](http://creativecommons.org/publicdomain/zero/1.0/) for more
information.

In summary, you are entitled to use this encoded model in absolutely any
manner you deem suitable, verbatim, or with modification, alone or embedded it
in a larger context, redistribute it, commercially or not, in a restricted way
or not.

  

To cite BioModels Database, please use: [Li C, Donizelli M, Rodriguez N,
Dharuri H, Endler L, Chelliah V, Li L, He E, Henry A, Stefan MI, Snoep JL,
Hucka M, Le Novere N, Laibe C (2010) BioModels Database: An enhanced, curated
and annotated resource for published quantitative kinetic models. BMC Syst
Biol., 4:92.](http://www.ncbi.nlm.nih.gov/pubmed/20587024)


