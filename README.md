# Bibliometric Analysis of Deep Learning Architectures Applied to MRI for ASD Classification

Replication materials for the paper submitted to ETCM 2026.

## Abstract

Bibliometric analysis of 2,025 Scopus-indexed publications on machine 
learning and deep learning applied to MRI for autism spectrum disorder 
classification (2018-2025). Uses a hybrid classification pipeline 
combining lexical pattern matching and zero-shot inference with 
DeBERTa-v3-large across seven model architecture categories.

## Repository Contents

- `query.txt` — Scopus search query and retrieval metadata
- `bibliometric_local.ipynb` — Main analysis notebook (Python 3.12)

## Requirements

```bash
pip install pandas numpy matplotlib seaborn scikit-learn transformers torch ipykernel
```

## Usage

1. Export results from Scopus using the query in `query.txt`
2. Save the export as `scopus.csv` in the same directory
3. Run `bibliometric_local.ipynb` sequentially

## Key Findings

- 2,025 publications retrieved (2018-2025)
- CNNs dominate with 49.0% of classified publications
- rs-fMRI publications outnumber sMRI 4:1 despite inferior meta-analytic performance
- Transformer-based architectures show lowest citation impact despite rapid growth
- Top 5 countries account for 68.7% of output

## Author

Jonathan Zambrano-Arriaga  
Facultad de Ingeniería en Electricidad y Computación  
Escuela Superior Politécnica del Litoral, ESPOL  
jonpzamb@espol.edu.ec