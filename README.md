[![GPLv3 License](https://img.shields.io/badge/License-GPL%20v3-yellow.svg)](https://opensource.org/licenses/)
[![Last version](https://img.shields.io/github/tag/alopgar/microDA.svg)](https://img.shields.io/github/tag/alopgar/microDA.svg)
[![CRAN_Status_Badge](http://www.r-pkg.org/badges/version/microDA)](https://cran.r-project.org/package=microDA)

# R-metagenomics
Pipeline for analysis of metagenomic sequences

This pipeline contains a post-processing analysis in R markdown for metagenomic analysis.

# Getting started
To use this pipeline, simply download the **Metagenomics_an.Rmd** file and change the options available in the `setup` and `init_variables` chunks.

## Dependencies
- **tidyverse**: `install.packages("tidyverse")`
- **microbiome**: `BiocManager::install("microbiome")` or `devtools::install_github("microbiome/microbiome")`
- **phyloseq**: `source('http://bioconductor.org/biocLite.R'); biocLite('phyloseq')`
- **vegan**: `install.packages("vegan")`
- **zCompositions**: `install.packages("zCompositions")`
- **easyCODA**: `install.packages("easyCODA")`
- **limma**: `BiocManager::install("limma")`
- **propr**: `install.packages("propr")`
- **nortest**: `install.packages("nortest")`
- **gridExtra**: `install.packages("gridExtra")`
- **plotly**: `install.packages("plotly")`
- **sunburstR**: `install.packages("sunburstR")`
- **ellipse**: `install.packages("ellipse")`
- **ggrepel**: `install.packages("ggrepel")`
- **ggordiplots**: `remotes::install_github("jfq3/ggordiplots")`
- **colortools**: `install.packages('colortools')`
- **microDA**: `devtools::install_github("alopgar/microDA")`

# Acknowledgements
This repository uses functions from multiple R packages. Please cite R and those R packages when using it.
