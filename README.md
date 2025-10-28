# scRNA File Formats

This repository demonstrates how to **read, access, and convert single-cell RNA sequencing (scRNA-seq) data** from various file formats into **Seurat objects** using **R**.  

It is designed for **beginners** in single-cell analysis, helping users understand different scRNA-seq file types and how to process them in R for downstream analysis.

---

## 🔹 Supported File Formats

| File Format | Description |
|------------|-------------|
| `.rds` | Fully processed Seurat objects |
| `.h5` | Raw and filtered 10x CellRanger feature-barcode matrices |
| `.mtx` | Matrix Market format (from CellRanger outputs) |
| `.loom` | Large-scale single-cell datasets |
| `.h5ad` | AnnData format (used in Python’s Scanpy; converted via SeuratDisk) |

---

## 🔹 Prerequisites

This project uses the following **R packages**:

- **Seurat** – For single-cell analysis  
- **SeuratDisk** – For converting and loading Seurat objects across different formats

---
### Dataset
https://drive.google.com/file/d/1PAxhBs8JLf95pFUgJN3qqMoF9uweE1TX/view?usp=drive_link

---
### Usage Guide

Clone this repository:

git clone https://github.com/Marydoss-25/scRNA-Data-analysis.git

---
### Installing Required Packages

```r
install.packages("Seurat")
install.packages("remotes")
remotes::install_github("mojaveazure/seurat-disk")


