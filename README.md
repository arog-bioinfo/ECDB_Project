# ECDB_Project

This repository contains practical work for the course **Extração de Conhecimento de Dados Biológicos (2024/2025)**. It includes two distinct subprojects: one in **R** and one in **Python**, each focusing on a different biological dataset and task.

---

## 🔹 R Project – Lung Adenocarcinoma Analysis (TCGA, GDC)

### Overview
This project involves the analysis of gene expression data using the R programming language and Bioconductor packages.

### Dataset
We use the **Lung Adenocarcinoma (TCGA, GDC)** dataset, available at [cBioPortal](https://www.cbioportal.org/study/summary?id=luad_tcga_pan_can_atlas_2018). This dataset contains gene expression profiles and associated clinical metadata from lung adenocarcinoma samples.

---

## 🔸 Python Project – Ames Mutagenicity Prediction

### Objective
To build a machine learning model that predicts whether a drug is mutagenic based on its SMILES string.

### Dataset Description
The Ames test is a short-term bacterial reverse mutation assay that detects compounds capable of causing genetic mutations. It remains a widely used method for evaluating chemical mutagenicity.

- **Type**: Binary classification  
- **Input**: Drug SMILES string  
- **Output**: Mutagenic (1) or Not Mutagenic (0)  
- **Size**: 7,273 drugs  
- **Source**: Aggregated from four publications

### References
[1] Xu, Congying, et al. “In silico prediction of chemical Ames mutagenicity.” *Journal of Chemical Information and Modeling*, 52.11 (2012): 2840–2847.

---

## Repo Structure   
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
│       ├── images/                 
│       └── relatorio\_grupo1.rmd
│
├── .gitignore
├── EEUMLOGO.png
├── LICENSE
└── README.md

```

## Team
- Artur Gomes | pg55692
- Catarina Gomes | pg55694
- Maria Carvalho | pg55130
