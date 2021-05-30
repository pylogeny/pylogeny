# Pylogeny: Python Packages for Phylogenetic Studies in Linguistics and Beyond

Pylogeny refers to a couple of individual Python packages which can be used in isolation but also in combination. What the packages have in common is a unified data structure that is used to carry out certain phylogenetic operations (parsimony, likelihood, etc.). 

## Authors

The current team which is actively developing the packages in the Pylogeny series consists of the following people:

Name | Year | Affiliation
--- | --- | ---
Johann-Mattis List | 2021- | Max Planck Institute for Evolutionary Anthropology
Taraka Rama | 2021- | University of North Texas
Robert Forkel | 2021- | Max Planck Institute for Evolutionary Anthropology

## Pylogeny Packages

Package | Description
--- | ---
[pylodata](https://github.com/pylogeny/data) | Package provides routines to load data (e.g. from LingPy Wordlists), and also offers basic datasets for testing.
[pylocluster]((https://github.com/pylogeny/cluster) | Package provides routines for clustering data (UPGMA, Neighbor-Joining).
[pylotree](https://github.com/pylogeny/tree) | A wrapper of the Python newick package which provides some extra functionalities for Pylogeny packages.
[pylostatistics](https://github.com/pylogeny/statistics) | A small package providing some statistic functions that would otherwise require "heavy" dependencies like SciPy and NumPy
[pyloparsimony](https://github.com/pylogeny/parsimony) | Package for parsimony operations.
[pylolikelihood](https://github.com/pylogeny/likelihood) | Package for likelihood computations (pruning algorithms for different models).

## Pylogeny Gallery

We do not aim to provide heavy plotting machinery for the operations in our packages, but we offer a [gallery](htts://github.com/pylogeny/gallery) in which we will provide examples of how plots can be done with the help of thirdparty packages.
