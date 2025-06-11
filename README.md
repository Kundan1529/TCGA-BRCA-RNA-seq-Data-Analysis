# TCGA-BRCA-RNA-seq-Data-Analysis Gene Expression Clustering (TCGA BRCA)
 This project analyzes TCGA BRCA RNA-seq gene expression data to explore underlying patterns in breast cancer samples. The primary objective is to cluster patient samples based on gene expression profiles using unsupervised learning.

 # 🔍 Key Steps 
 *  Data Loading & Preprocessing:
    * Imported log2-transformed RNA-seq data, transposed the dataset, handled missing and infinite values, and prepared a sample × gene matrix.

 * Exploratory Data Analysis:
    * Visualized gene expression distribution across samples using histograms and descriptive statistics.

 *  Clustering:
   * Applied K-Means clustering to group samples based on gene expression similarity, visualized the cluster label distribution.
 # 🛠 Tools & Libraries
    * pandas, numpy – Data handling

    * matplotlib, seaborn – Visualization

    * scikit-learn – Clustering with KMeans

