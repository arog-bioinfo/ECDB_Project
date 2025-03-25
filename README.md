# ECDB_Project : Lung Adenocarcinoma Analysis (TCGA, GDC)

## Overview
This repository contains the practical work for the course *Extração de Conhecimento de Dados Biológicos (2024/2025)*. The project involves the analysis of gene expression data using the R programming language and Bioconductor packages. 

## Dataset
We are using the **Lung Adenocarcinoma (TCGA, GDC)** dataset, available at [cBioPortal](https://www.cbioportal.org/study/summary?id=luad_tcga_pan_can_atlas_2018). This dataset contains gene expression data for lung adenocarcinoma samples and associated clinical metadata.

## Project Structure   
```
├── data/                # Raw and processed datasets
├── scripts/             # R and Rmd scripts for analysis
├── results/             # Generated reports, figures, and outputs
├── report/              # Final report in HTML format
├── README.md            # Project documentation
```

## Objectives
The project is divided into two phases:
### **Phase 1 (Due: April 3, 2024)**
- Data acquisition and preprocessing
- Data summary (descriptive statistics and visualizations)
- Univariate statistical analysis
- Differential expression and enrichment analysis

### **Phase 2 (Due: May 8, 2024)**
- Clustering (genes/samples), dimensionality reduction, and MDS
- Predictive analysis (classification/regression with at least two models)
- Gene selection and importance evaluation

## Methodology
The following tools and techniques will be used:
- **Data Processing**: R, Bioconductor, tidyverse
- **Visualization**: ggplot2, heatmaps, PCA plots
- **Statistical Analysis**: limma, DESeq2
- **Machine Learning**: caret, randomForest, SVM

## Reproducibility
- All analyses will be performed in R Markdown and exported as HTML reports.
- R scripts (`.R` or `.Rmd`) will be provided to ensure full reproducibility.
- The analysis workflow and key results will be documented in the final report.

## Team
- Artur Gomes | pg55692
- Catarina Gomes | pg55694
- Maria Carvalho | pg55130
