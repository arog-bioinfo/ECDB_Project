# ECDB_Project : Lung Adenocarcinoma Analysis (TCGA, GDC)

## Overview
This repository contains the practical work for the course *Extração de Conhecimento de Dados Biológicos (2024/2025)*. The project involves the analysis of gene expression data using the R programming language and Bioconductor packages. 

## Dataset
We are using the **Lung Adenocarcinoma (TCGA, GDC)** dataset, available at [cBioPortal](https://www.cbioportal.org/study/summary?id=luad_tcga_pan_can_atlas_2018). This dataset contains gene expression data for lung adenocarcinoma samples and associated clinical metadata.

## Project Structure   
```

ECDB\_PROJECT/
├── trabalho\_py/                    # Python Project
│   ├── data\_csv/                   # CSV data for Python
│   │   ├── ames\_features.csv
│   │   ├── ames\_outputs.csv
│   │   └── README.md
│   └── relatorio\_grupo1.ipynb      # Jupyter Notebook
│
├── trabalho\_r/                     # R project
│   ├── data\_csv/                   # CSV data for R
│   │   ├── dge\_deseq2.csv
│   │   └── enrichment\_analysis.csv
│   ├── HTMLs/                      # Rendered R Markdown reports
│   │   ├── relatorio\_grupo1\_fase1.html
│   │   └── relatorio\_grupo1\_fase2.html
│   └── scripts\_R/                  # R scripts and Rmd
│       ├── images/                 # Images used in R reports
│       └── relatorio\_grupo1.rmd
│
├── .gitignore
├── EEUMLOGO.png
├── LICENSE
└── README.md

```




## Objectives
The project is divided into two phases:
### **Phase 1**
- Data acquisition and preprocessing
- Data summary (descriptive statistics and visualizations)
- Univariate statistical analysis
- Differential expression and enrichment analysis

### **Phase 2**
- Clustering (genes/samples), dimensionality reduction, and MDS
- Predictive analysis (classification/regression with at least two models)
- Gene selection and importance evaluation

## Methodology

The following tools and techniques were used throughout the analysis, organized by their role in the workflow:

- **Data Acquisition & Processing**  
  Packages: `TCGAbiolinks`, `SummarizedExperiment`, `Biobase`, `tidyverse`  
  Used for downloading, filtering, and organizing genomic datasets, particularly from TCGA.

- **Visualization**  
  Packages: `ggplot2`, `ggbeeswarm`, `pheatmap`, `gplots`, `RColorBrewer`, `factoextra`  
  Applied to generate scatter plots, beeswarm plots, heatmaps, and enhanced visual summaries of clustering and dimensionality reduction.

- **Statistical Analysis**  
  Packages: `DESeq2`, `edgeR`, `genefilter`, `AnnotationDbi`, `org.Hs.eg.db`  
  Utilized for differential gene expression analysis, statistical filtering, and annotation mapping.

- **Enrichment Analysis**  
  Packages: `fgsea`, `org.Hs.eg.db`, `AnnotationDbi`  
  Conducted gene set enrichment analysis and mapped gene identifiers to biological pathways and functions.

- **Dimensionality Reduction**  
  Packages: `Rtsne`, `factoextra`  
  Used for reducing data dimensionality and visualizing sample separation.

- **Clustering**  
  Packages: `pheatmap`, `gplots`  
  Implemented hierarchical clustering and heatmap visualizations to group similar samples or genes.

- **Machine Learning & Predictive Modeling**  
  Packages: `caret`, `rpart`, `rsample`  
  Employed for model training, validation, and evaluation, especially in classifying sample groups or predicting outcomes.


## Reproducibility
- All analyses will be performed in R Markdown and exported as HTML reports.
- R scripts (`.R` or `.Rmd`) will be provided to ensure full reproducibility.
- The analysis workflow and key results will be documented in the final report.

## Team
- Artur Gomes | pg55692
- Catarina Gomes | pg55694
- Maria Carvalho | pg55130
