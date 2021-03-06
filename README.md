# Melodia
## Protein Structure Analysis

**Melodia** is a Python library for computing Differential Geometry
and Knot Theory descriptors of protein structures. 

## Installation [Anaconda Python](https://www.anaconda.com/products/individual)

We recommend using [Mamba](https://github.com/mamba-org/mamba) for installation.

```shell
conda install mamba -n base -c conda-forge
```
It is recommended the creation of a new environment for **Melodia**.

```shell
conda create --name melodia python=3.9
```
```shell
conda activate melodia
```

**Melodia** requires [Jupyterlab](https://jupyter.org/), [NGL Viewer](https://github.com/nglviewer/nglview), [scikit-learn](https://scikit-learn.org/stable) and [seaborn](https://seaborn.pydata.org/).

```shell
mamba install jupyterlab
```

```shell
mamba install -c conda-forge nglview
```

```shell
mamba install -c conda-forge scikit-learn
```

```shell
mamba install -c conda-forge seaborn
```

The examples need [dill](https://github.com/uqfoundation/dill) and [pyarrow](https://github.com/apache/arrow).

```shell
mamba install -c anaconda dill
```
```shell
mamba install -c conda-forge pyarrow
```

To build and install **Melodia**:

```shell
python setup.py install
```
### Authors
- Rinaldo W. Montalvão, PhD
- Antonio Marinho da Silva Neto, PhD
- William R. Pitt, PhD

### References
- Montalvão R, Smith R, Lovell S, Blundell T: CHORAL: a differential geometry approach to the prediction of the cores of protein structures. Bioinformatics. 2005, 21: 3719-3725.
- Chang PL, Rinne AW, Dewey TG: Structure alignment based on coding of local geometric measures. BMC Bioinformatics. 2006, 7:346.
- Leung H, Montaño B, Blundell T, Vendruscolo M, Montalvão R: ARABESQUE: A tool for protein structural comparison using differential geometry and knot theory. World Res J Peptide Protein. 2012, 1: 33-40.
- Pitt WR, Montalvão R, Blundell T: Polyphony: superposition independent methods for ensemble-based drug discovery. BMC Bioinformatics. 2014, 15:324 
- Marinho da Silva Neto A, Reghim Silva S, Vendruscolo M, Camilloni C, Montalvão R: A Superposition Free Method for Protein Conformational Ensemble Analyses and Local Clustering Based on a Differential Geometry Representation of Backbone. Proteins: Structure, Function, and Bioinformatics. 2018, 87(4):302-312
- Marinho da Silva Neto A, Montalvão R, Gondim Martins DB, Lima Filho JL, Madeiros Castelletti CH: A model of key residues interactions for HPVs E1 DNA binding domain-DNA interface based on HPVs residues conservation profiles and molecular dynamics simulations, Journal of Biomolecular Structure and Dynamics. 2019, 38(12):3720-3729.
