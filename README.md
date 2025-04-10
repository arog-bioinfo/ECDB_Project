# ECDB_Project : Lung Adenocarcinoma Analysis (TCGA, GDC)

## Overview
This repository contains the practical work for the course *Extração de Conhecimento de Dados Biológicos (2024/2025)*. The project involves the analysis of gene expression data using the R programming language and Bioconductor packages. 

## Dataset
We are using the **Lung Adenocarcinoma (TCGA, GDC)** dataset, available at [cBioPortal](https://www.cbioportal.org/study/summary?id=luad_tcga_pan_can_atlas_2018). This dataset contains gene expression data for lung adenocarcinoma samples and associated clinical metadata.

## Project Structure   
```
├── html/                # HTML outputs
│   └── [relatorio_grupo1_fase1]
│
├── scripts/             # R and Rmd scripts
│   └── [relatorio_grupo1_fase1]
│
├── relatorio_grupo1_fase1_files/            
└── README.md            # Project documentation

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
The following tools and techniques will be used:
- **Data Processing**: R, Bioconductor, tidyverse
- **Visualization**: ggplot2, heatmaps, PCA plots
- **Statistical Analysis**: DESeq2, edgeR, limma, genefilter
- **Enrichment Analysis**: fgsea, org.Hs.eg.db, AnnotationDbi
- **Machine Learning**: caret, rpart, rsample
- **Dimensionality Reduction**: Rtsne, factoextra
- **Clustering**: pheatmap, gplots

## Reproducibility
- All analyses will be performed in R Markdown and exported as HTML reports.
- R scripts (`.R` or `.Rmd`) will be provided to ensure full reproducibility.
- The analysis workflow and key results will be documented in the final report.

## Team
- Artur Gomes | pg55692
- Catarina Gomes | pg55694
- Maria Carvalho | pg55130
