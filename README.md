# Introduction

single cell RNA seq is used extensively in fundamental and translational research to identify cell populations within a biological sample, infer the connectictivity and relationships between these populations and identify the effects of experimental conditions on the transcriptome of these populations. 
There are numerous pipelines and tools available to perform analysis of such data.  We will use the well established Bioconductor [pipeline](https://bioconductor.org/books/release/OSCA/) in R to perform full analysis of a human PBMC dataset starting from the raw count matrix.

# Objectives

During the course, the students will learn to:

- manipulate a SingleCellExperiment R object
- perform quality control and low quality cell exclusion
- understand and perform  data normalization
- perform dimentionaly reduction
- cluster the cells and identify marker genes
- perform cell type annotation
- integrate multiple samples (patients), analyse inter-patients variability
- understand batch correction. What to correct, when to correct?
- combine cells into pseudobulk and perform differential gene expression analysis with DEseq2

# Flow of the course

The data will be made available on Github the Morning of the first day.

- On day 1 the students will follow a step by a step analysis [workflow](tutorialScRNAseqAnalysis.Rmd).

- On day 2, the students will analyse other samples (provided by the tutor) on their own using the workflow of the first day as a template and will integrate the samples together and study inter donor variability.


# R installation (IMPORTANT)

please install [R 4.5.2](https://cran.rstudio.com/), and [Rstudio](https://posit.co/download/rstudio-desktop/) prior to the course.

Windows user also need to install [Rtools45](https://cran.r-project.org/bin/windows/Rtools/rtools45/rtools.html) to install some Bioconductor packages.
  
