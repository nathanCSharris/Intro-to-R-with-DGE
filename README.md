## Introduction to R and differential gene expression (DGE) analysis

| Audience | Computational Skills | Prerequisites | Duration |
:----------|:----------|:----------|:----------|
| Biologists | Beginner/Intermediate | None | 3-day workshop (~19.5 hours of trainer-led time)|

### Description
This repository has teaching materials for a **3-day**, hands-on **Introduction to R and differential gene expression (DGE) analysis** workshop. The workshop will introduce participants to the basics of R and RStudio and their application to differential gene expression analysis on RNA-seq count data.

R is a simple programming environment that enables the effective handling of data, while providing excellent graphical support. RStudio is a tool that provides a user-friendly environment for working with R. Together, R and RStudio allow participants to wrangle data, plot, and use DESeq2 to obtain lists of differentially expressed genes from RNA-seq count data.

This workshop is intended to provide both basic R programming knowledge AND its application. Participants should be interested in:

- using R for increasing their efficiency for data analysis
- visualizing data using R (ggplot2)
- using R to perform statistical analysis on RNA-seq count data to obtain differentially expressed gene lists

### Learning Objectives

1. **R syntax**: Understand the different 'parts of speech'.
2. **Data types structures in R**: Describe the various data types and data structures.
3. **Data inspection and wrangling**: Demonstrate the utilization of functions and indices to inspect and subset data from various data structures.
4. **Visualizing data**: Demonstrate the use of the ggplot2 package to create plots for easy data visualization.
5. **Differential expression analysis for RNA-seq data:**
    - Perform QC on count data
    - Use DESeq2 to obtain a list of significantly differentially expressed genes
    - Visualize expression patterns of differentially expressed genes
    - Perform functional analysis on gene lists with R-based tools

> These materials are developed for a trainer-led workshop, but also amenable to self-guided learning.

### Lessons

* Scheule with links to lessons on **DGE on pseudocounts generated by *Salmon*** will be posted soon!
* [Click here for the schedule](https://hbctraining.github.io/Intro-to-R-with-DGE/schedule) with links to lessons on **DGE on counts from *STAR & FeatureCounts***


### Installation Requirements

1. Download the most recent versions of R and RStudio for your laptop:

 - [R](https://cran.r-project.org/) 
 - [RStudio](https://www.rstudio.com/products/rstudio/download/#download)

2. Packages to be installed:
    * [Click here for required packages](https://hbctraining.github.io/DGE_workshop#installation-requirements) for lessons on DGE with pseudocounts generated by Salmon 
    * [Click here for required packages](https://hbctraining.github.io/DGE_workshop_salmon#installation-requirements) for lessons on DGE on counts from STAR-Featurecounts


### Dataset

All the files used for the above lessons are linked within as needed.

***

*These materials have been developed by members of the teaching team at the [Harvard Chan Bioinformatics Core (HBC)](http://bioinformatics.sph.harvard.edu/). These are open access materials distributed under the terms of the [Creative Commons Attribution license](https://creativecommons.org/licenses/by/4.0/) (CC BY 4.0), which permits unrestricted use, distribution, and reproduction in any medium, provided the original author and source are credited.*

* *Some materials used in these lessons were derived from work that is Copyright © Data Carpentry (http://datacarpentry.org/). 
All Data Carpentry instructional material is made available under the [Creative Commons Attribution license](https://creativecommons.org/licenses/by/4.0/) (CC BY 4.0).*
