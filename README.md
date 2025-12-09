# Transcriptomic Analysis of Cisplatin Resistance in Lung Cancer 🧬## 📌 Project Overview
This repository contains the bioinformatics pipeline and analysis scripts for investigating the **molecular mechanisms of Cisplatin resistance** in Non-Small Cell Lung Cancer (NSCLC). 

Using RNA-Seq data from **A549 cell lines** (Parental vs. Cisplatin-Resistant), this study aims to identify key differentially expressed genes (DEGs) and reconstruct Protein-Protein Interaction (PPI) networks to uncover potential biomarkers for drug resistance.

---## 🚀 Workflow & Methodology

The analysis pipeline consists of both **Python** and **R** workflows, integrated to handle data preprocessing and statistical analysis:1.  **Data Preprocessing (Python):** - Quality control and data cleaning using `Pandas` and `NumPy`.    - Handling missing values and normalization preparation.2.  **Differential Expression Analysis (R):** - Statistical analysis using **DESeq2** to identify significant DEGs between resistant and sensitive cell lines.    - Thresholds: |log2FoldChange| > 1 and p-adj < 0.05.3.  **Functional Enrichment (R):**    - Gene Ontology (GO) and KEGG pathway analysis using `clusterProfiler`.4.  **Network Reconstruction:**    - Mapping DEGs to **STRING DB** to visualize PPI networks.    - Network topology analysis (Hub gene identification) using **Cytoscape**.

---## 📊 Key Findings* **Identified Biomarkers:** Significant upregulation of **AKR1C1** and **AKR1C2** genes was observed in the resistant phenotype, suggesting a metabolic shift contributing to drug detoxification.* **Pathway Enrichment:** Enriched pathways include *Chemical carcinogenesis* and *Drug metabolism (cytochrome P450)*.* **PPI Network:** Reconstructed network revealed distinct clusters associated with oxidoreductase activity.

---## 🛠️ Tech Stack & Dependencies### Languages* ![Python](https://img.shields.io/badge/Python-3.8%2B-blue)* ![R](https://img.shields.io/badge/R-4.0%2B-blue)### Libraries & Packages* **R:** `DESeq2`, `ggplot2`, `clusterProfiler`, `pheatmap`, `tidyverse`* **Python:** `Pandas`, `NumPy`, `Matplotlib`, `Seaborn`

---## 📂 Repository Structure
├── data/               # Raw and processed datasets (if public)
├── scripts/            # Source code for analysis
│   ├── 01_preprocessing.py
│   └── 02_deseq2_analysis.R
├── results/            # Output plots (Volcano plots, Heatmaps) and tables
└── README.md           # Project documentation


---

## 👩‍💻 Author

**Maryam Najafi** *Undergraduate Researcher | Bioinformatics & Molecular Genetics* This project was conducted as an independent research initiative to bridge Wet-Lab knowledge with Computational Biology applications.

📧 mariyamrnj8444@gmail.com  
