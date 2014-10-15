# BIOMD0000000457: BIOMD0000000457

## Installation

Download this repository, and install with distutils

`python setup.py install`

Or, install using pip

`pip install git+https://github.com/biomodels/BIOMD0000000457.git`

To install a specific version (in this example, from the 2014-09-16 BioModels release)

`pip install git+https://github.com/biomodels/BIOMD0000000457.git@20140916`


# Model Notes


Firczuk2013 - Eukaryotic mRNA translation machinery

This is a model of _Saccharomyces cerevisiae_ mRNA translation which includes
the initiation, elongation and termination phases. The model is for 20 condon
mRNAs. The building of a multi-factor complex in initiation and also the
different processes in elongation and termination are modelled in detail. The
model takes into account that ribosomes cover more than one codon of mRNA so
that the movement of ribosomes are effectively blocked by other ribosomes
several codons downstream. It is assumed that 15 codons are occupied by each
ribosome. This blocking effect is considered in reaction R18 in initiation and
also reaction R26, the reaction where translocation of ribosomes takes place
in elongation. The kinetic functions of these two reactions are based on
MacDonald et al. 1968 and Heinrich & Rapaport 1980. All other kinetic
functions follow mass-action kinetics. The concentrations of transfer RNA
species (Met-tRNA, aa-tRNA and tRNA in the model) are kept constant, while the
other species' concentrations can change in the course of the simulation. The
model describes the translation of a short mRNA with 20 codons. Therefore, all
reactions in the elongation cycle (R22, R23, R25, R26, R28 and R29) and the
corresponding species are replicated accordingly to model the species with
ribosomes bound at different positions. In summary, the model contains 165
different species and 141 reactions.

The value of the 56 rate constant parameters were estimated by fitting the
model against a series of experimental data consisting of modulation of the
various translation factors (Figures 2, 3 and S3). Overall the parameter
estimation was carried out over 212 different data points (steady states).

This model is described in the article:

[An in vivo control map for the eukaryotic mRNA translation
machinery](http://identifiers.org/pubmed/23340841)

Helena Firczuk, Shichina Kannambath, Jürgen Pahle, Amy Claydon, Robert Beynon,
John Duncan, Hans Westerhoff, Pedro Mendes and John EG McCarthy

Molecular Systems Biology. 9:635

Abstract:

Rate control analysis defines the in vivo control map governing yeast protein
synthesis and generates an extensively parameterized digital model of the
translation pathway. Among other non-intuitive outcomes, translation
demonstrates a high degree of functional modularity and comprises a non-
stoichiometric combination of proteins manifesting functional convergence on a
shared maximal translation rate. In exponentially growing cells, polypeptide
elongation (eEF1A, eEF2, and eEF3) exerts the strongest control. The two other
strong control points are recruitment of mRNA and tRNAi to the 40S ribosomal
subunit (eIF4F and eIF2) and termination (eRF1; Dbp5). In contrast, factors
that are found to promote mRNA scanning efficiency on a longer than-average
5′untranslated region (eIF1, eIF1A, Ded1, eIF2B, eIF3, and eIF5) exceed the
levels required for maximal control. This is expected to allow the cell to
minimize scanning transition times, particularly for longer 5′UTRs. The
analysis reveals these and other collective adaptations of control shared
across the factors, as well as features that reflect functional modularity and
system robustness. Remarkably, gene duplication is implicated in the fine
control of cellular protein synthesis.

This model is hosted on [BioModels Database](http://www.ebi.ac.uk/biomodels/)
and identified by:
[BIOMD0000000457](http://identifiers.org/biomodels.db/BIOMD0000000457) .

To cite BioModels Database, please use: [BioModels Database: An enhanced,
curated and annotated resource for published quantitative kinetic
models](http://identifiers.org/pubmed/20587024) .

To the extent possible under law, all copyright and related or neighbouring
rights to this encoded model have been dedicated to the public domain
worldwide. Please refer to [CC0 Public Domain
Dedication](http://creativecommons.org/publicdomain/zero/1.0/) for more
information.


