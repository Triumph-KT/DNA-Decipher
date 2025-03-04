# Genomic-Data-Clustering-PCA-KMeans

Applied unsupervised machine learning techniques to analyze bacterial genome sequences, identifying inherent biological patterns and validating the triplet codon structure through clustering and dimensionality reduction.

## Project Overview

This project analyzes a bacterial genome to uncover underlying biological structures using unsupervised learning techniques. Specifically, it validates the principle of triplet codon organization in genetic sequences.

## Dataset

- 300Kbp genome sequence from *Caulobacter Crescentus*.
- K-mer frequency features (nucleotide substrings of lengths 1–4).

## Objectives

- Reduce dimensionality to reveal biological structures.
- Apply clustering to detect genetic patterns.
- Validate the triplet codon structure through data-driven methods.

## Methods

- Feature extraction from genomic sequences.
- Dimensionality reduction using **Principal Component Analysis (PCA)**.
- Clustering with **K-Means (k=7)**.
- Visualization of principal components and cluster separation.

## Results

- Captured significant variance through PCA, highlighting patterns in **3-letter codons**.
- Formed seven clusters aligning with biological reading frames and strand orientation.
- Reinforced the biological principle of triplet codon structure through unsupervised learning.

## Technologies Used

- Python
- Pandas
- Scikit-learn
- Matplotlib
- Seaborn

## How to Run

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/genomic-data-clustering.git
    ```

2. Install required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

3. Launch Jupyter Notebook:
    ```bash
    jupyter notebook
    ```

4. Open and run the notebook to reproduce the results.
