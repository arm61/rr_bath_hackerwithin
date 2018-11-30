# ESI of my reproducible paper

[Andrew R. McCluskey](https://orcid.org/0000-0003-3381-5911)

[a.r.mccluskey@bath.ac.uk](mailto:a.r.mccluskey@bath.ac.uk)


This is the electronic supplementary information (ESI) associated with the publication "Bayesian determination of the effect of a deep eutectic solvent on the structure of lipid monolayers".
This ESI provides full details of the analyses performed in the work and access to an automated analysis workflow, through this we aim to provide better access to analysis reproducibility.
For more information about reproducible workflows in Python, check out [Tania Allard's talk from Pycon2018](http://bitsandchips.me/Talks/PyCon.html#/title).

## Analysis

This ESI aims to provide a fully reproducible workflow to the data analysis present within the paper.

Requirements:

- anaconda or miniconda Python
- [REVTeX](https://journals.aps.org/revtex)

To reproduce the analysis, plot the figures, and build the paper, run the following:

```
conda create -n paper_env -c bioconda snakemake

source activate paper_env

snakemake
```

## Acknowledgements

A. R. M. is grateful to the University of Bath and Diamond Light Source for co-funding a studentship (Studentship Number STU0149).
