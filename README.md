# Seurat single-cell RNA-seq analysis

This repository contains one of the two projects for my Transcriptomics exam I took as part of my "Bioinformatics for Computational Genomics" MSc at University of Milano. 

The purpose of this project was carrying out a Single Cell RNA-Seq analysis (through the [seurat](https://cran.r-project.org/web/packages/Seurat/index.html) package) over genes expression data coming from samples coming from a single tissue. The count table, that can be found in the _data/_ folder, comes from the [PanglaoDB](https://panglaodb.se/) repository and was obtained from an adult mouse brain cortex in relation to the following study: _Zeisel, Amit, et al. "Molecular architecture of the mouse nervous system." Cell 174.4 (2018): 999-1014_
In particular, the steps of the analysis included cell quality analysis, dimensionality reduction, cells' clustering and retrieval of putative marker genes for each of the clusters.The marker genes research has been performed mainly in literature and on [Tabula Muris](https://tabula-muris.ds.czbiohub.org/)

The R source code is included in the _scRNA\_analysis.Rmd_ file with some brief explanation about each section, and the slides I showed as my final presentation are available as a pptx file.
