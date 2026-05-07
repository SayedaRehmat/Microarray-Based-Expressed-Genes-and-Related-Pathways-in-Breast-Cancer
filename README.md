# Microarray-Based Expression Profiling for Identification of Differentially Expressed Genes and Related Pathways in Breast Cancer

## Overview
This project focuses on identifying Differentially Expressed Genes (DEGs) and associated biological pathways involved in breast cancer using microarray gene expression analysis. The study utilizes publicly available microarray data from the GEO database and applies statistical and bioinformatics approaches to explore molecular mechanisms underlying breast cancer progression.

---

## Project Objectives
- Identify significantly differentially expressed genes between breast cancer and normal tissue samples.
- Discover enriched biological pathways associated with breast cancer.
- Analyze the role of key genes involved in cancer progression and signaling pathways.

---

## Dataset Information

| Attribute | Details |
|---|---|
| Dataset ID | GSE15852 |
| Source | GEO (Gene Expression Omnibus) |
| Platform | Affymetrix Human Genome U133A Array |
| Samples | 43 Breast Tumor Samples |
| Controls | 43 Normal Samples |

---

## Methodology

### 1. Data Acquisition
The dataset was downloaded from the GEO database and imported into the analysis environment.

### 2. Data Preprocessing
- Background correction
- Normalization
- Quality control assessment using box plots

### 3. Exploratory Data Analysis
- UMAP visualization for sample clustering
- Detection of separation between tumor and normal samples

### 4. Differential Expression Analysis
Genes were filtered using:
- p-value < 0.05
- Fold Change (FC) > 1 or FC < -1

A total of 22,283 DEGs were identified.

### 5. Visualization
- Volcano Plot
- Voom Plot
- Heatmaps and clustering analysis

### 6. Pathway Enrichment Analysis
Enriched pathways were identified to understand molecular mechanisms associated with breast cancer progression.

---

## Results

### Quality Control
Box plots confirmed successful normalization and comparable distributions across samples.

### UMAP Analysis
Tumor samples clustered separately from normal samples, indicating clear biological differences between disease and healthy conditions.

### Significant Pathways Identified

| Pathway | Number of Genes |
|---|---|
| Pathways in Cancer | 85 |
| Breast Cancer Pathway | 26 |
| Proteoglycans in Cancer | 49 |

---

## Key Genes Identified

### Upregulated Genes
- LEF1
- ESR1
- FZD4
- JUN
- HES1
- FLT4

### Downregulated Genes
- RB1
- ERBB2
- FGFR1
- EGFR
- CTNNB1
- FGF18

---

## Biological Interpretation

### Wnt Signaling Pathway
Genes such as LEF1, FZD4, and WNT5A suggest activation of Wnt signaling, which contributes to:
- Tumor growth
- Cell survival
- Metastasis
- Therapy resistance

### Estrogen Signaling
Upregulation of ESR1 indicates estrogen receptor-positive breast cancer characteristics.

### Cell Cycle Dysregulation
- CDK4 upregulation promotes uncontrolled cell division.
- RB1 downregulation removes important cell-cycle checkpoints.

### Growth Factor Signaling
Altered expression of FGFR1, IGF1R, and EGFR highlights changes in tumor growth and survival pathways.

---

## Conclusion
This project successfully identified important gene expression changes and enriched biological pathways involved in breast cancer. The findings contribute to understanding the molecular basis of breast cancer and may support:
- Biomarker discovery
- Personalized medicine
- Identification of therapeutic targets

---

## Tools & Technologies
- R Programming
- Bioconductor Packages
- GEO Database
- Microarray Analysis
- UMAP Visualization
- Pathway Enrichment Analysis

---

## Author
**Sayeda Rehmat**  
