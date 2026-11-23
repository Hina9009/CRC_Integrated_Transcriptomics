# Integrated Bulk and Single-Cell Transcriptomic Analysis of Colorectal Cancer

## Overview

This repository contains R scripts supporting an integrated transcriptomic study of colorectal cancer (CRC). The analysis combines bulk RNA-sequencing data from TCGA-COAD and TCGA-READ with single-cell RNA-sequencing data from GSE221575 to investigate cell-cycle-associated genes and their prognostic relevance.

## Analysis Workflow

1. Differential expression analysis using DESeq2.
2. Weighted gene co-expression network analysis (WGCNA).
3. Identification and characterization of seven candidate genes: CDK1, CHEK1, CEP55, BUB1, NEK2, ECT2, and MAD2L1.
4. Single-cell RNA-sequencing analysis using Seurat to examine gene expression across cell populations, particularly cycling tumor-associated cells.
5. Exploratory survival analysis and LASSO-Cox regression to investigate the CHEK1/MAD2L1 prognostic signature.

## Data Sources

- TCGA-COAD and TCGA-READ: Genomic Data Commons (GDC).
- GSE221575: Gene Expression Omnibus (GEO).

## Software

The analyses were conducted in R using packages including TCGAbiolinks, DESeq2, WGCNA, Seurat, survival, and glmnet.

## Reproducibility

The analytical scripts and parameter settings are provided in this repository. 
## Study Scope

The prognostic analysis is exploratory.
