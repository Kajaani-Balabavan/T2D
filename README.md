[ # T2D
Prioritization of top GWAS SNPs and genes in type 2 diabetes ]: #

# **Integrating Temporal Gene Expression Dynamics with GWAS Signals for Causal Gene Prioritization in Type 2 Diabetes (T2D)**

## **Overview**
This project aims to prioritize causal genes associated with Type 2 Diabetes (T2D) by integrating temporal gene expression dynamics with GWAS signals. Using advanced machine learning techniques like Graph Neural Networks (GNNs) and Positive-Unlabeled (PU) learning, we model temporal gene regulation and validate findings experimentally using CRISPR data. The project also addresses population bias by incorporating cross-ancestry datasets.

**Key Objectives:**
1. Integrate GWAS and time-series RNA-seq data.
2. Model temporal gene co-expression networks using GNNs.
3. Prioritize candidate genes using PU-learning.
4. Validate top-ranked genes using CRISPR screens.
5. Address population bias by analyzing diverse cohorts (e.g., AGEN, H3Africa).

## **Datasets**
The following datasets are used in this project:
- **GWAS Summary Statistics**:
  - DIAGRAM Consortium T2D GWAS
  - UK Biobank T2D GWAS
- **RNA-Seq Data**:
  - HPAP Pancreatic Islet Time-Series RNA-Seq
  - Adipocyte Temporal Expression Data
- **GTEx Tissue-Specific Expression Data**
- **Islet-Specific eQTLs and Chromatin Accessibility Data**
- **Human Islet Single-Cell RNA-Seq Datasets**
- **CRISPR Validation Datasets**
- **Cross-Ancestry Data**:
  - AGEN (Asian Genetic Epidemiology Network)
  - H3Africa (Human Heredity and Health in Africa)

## **Methodology**
The project follows these steps:
1. **Data Integration and Preprocessing**:
   - Merge GWAS summary statistics with RNA-seq data.
   - Normalize and annotate datasets.
2. **Dynamic Network Analysis**:
   - Use GNNs to model temporal gene co-expression modules.
3. **PU-Learning Prioritization**:
   - Rank candidate genes based on GWAS signals and dynamic expression patterns.
4. **Validation**:
   - Validate top-ranked genes using CRISPR data.
5. **Population Bias**:
   - Perform fine-mapping and validation in non-European populations.

<!-- ## **Folder Structure**
The repository is organized as follows:

```
project-root/
│
├── README.md                     # Project overview and instructions
├── LICENSE                       # License file (if applicable)
├── requirements.txt              # Python dependencies
│
├── data/                         # Raw and processed datasets
│   ├── raw/                      # Raw datasets (e.g., GWAS, RNA-seq, CRISPR)
│   └── processed/                # Preprocessed and unified datasets
│
├── notebooks/                    # Jupyter notebooks for exploratory analysis
│   ├── data_preprocessing.ipynb  # Notebook for data cleaning and merging
│   ├── gnn_analysis.ipynb        # Notebook for GNN modeling
│   ├── pu_learning.ipynb         # Notebook for PU-learning prioritization
│   └── validation.ipynb          # Notebook for CRISPR validation
│
├── src/                          # Source code for the project
│   ├── data_preprocessing.py     # Scripts for data integration and preprocessing
│   ├── gnn_model.py              # Scripts for GNN implementation
│   ├── pu_learning.py            # Scripts for PU-learning prioritization
│   ├── validation.py             # Scripts for CRISPR validation
│   └── utils.py                  # Utility functions (e.g., visualization, metrics)
│
├── results/                      # Outputs from the analysis
│   ├── ranked_genes.csv          # Ranked list of prioritized genes
│   ├── validated_genes.csv       # Validated genes from CRISPR screens
│   └── visualizations/           # Plots and charts
│
└── reports/                      # Final reports and documentation
    ├── final_report.pdf          # Comprehensive project report
    └── presentation_slides.pptx  # Presentation slides
```

## **How to Run the Code**
1. **Clone the Repository**:
   ```bash
   git clone https://github.com/your-repo-url.git
   cd project-root
   ```

2. **Install Dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

3. **Run Data Preprocessing**:
   ```bash
   python src/data_preprocessing.py
   ```

4. **Train GNN Model**:
   ```bash
   python src/gnn_model.py
   ```

5. **Perform PU-Learning Prioritization**:
   ```bash
   python src/pu_learning.py
   ```

6. **Validate Results**:
   ```bash
   python src/validation.py
   ```

7. **Generate Visualizations**:
   Open the relevant Jupyter notebooks in the `notebooks/` folder and run the cells. -->

## **Contributors**
- Kajaani B. (200279N)
- Kobinath A. (200308F)
- Rajeevan Y. (200501P)
- Vibulan J. (200677H)

## **License**
This project is licensed under the MIT License. See the `LICENSE` file for details.
