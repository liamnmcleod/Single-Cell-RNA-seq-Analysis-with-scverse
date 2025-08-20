# Single-Cell-RNA-seq-Analysis-with-scverse
scRNA and snRNA-seq workflows with scverse tools (Scanpy + scvi-tools) integrated with PyTorch

Reproducible single-cell RNA-seq analysis using the scverse ecosystem  
(Scanpy, scvi-tools, anndata) with PyTorch-backed variational models.
From raw counts to annotated clusters, differential expression, and clean figures.



                                                  Data Availability

Alzheimer's snRNA data available from: https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE138852 
(A single-cell atlas of entorhinal cortex from individuals with Alzheimer's disease reveals cell-type-specific gene expression regulation) 
(Grubman et al, 2019). 


scRNA SARS-CoV-2 lung data from: https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSM5226574 
A molecular single-cell lung atlas of lethal COVID-19
(Melms et al, 2021). 


scRNA Immune Phenotype data from: https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE114725 
Single-cell Map of Diverse Immune Phenotypes in the Breast Tumor Microenvironment
(Azizi et al 2019).






## Features
- **QC & filtering:** mitochondrial/ribosomal metrics, doublet flag support  
- **Normalization:** log1p or scvi-tools normalized layers  
- **Batch integration:** **scVI** latent space (`X_scVI`) — runs on CPU or **GPU via PyTorch**  
- **Clustering & UMAP:** neighborhood graph, Leiden/UMAP  
- **Automated annotation:** marker panels + per-cluster scoring  
- **Differential expression:** `model.differential_expression(...)` with FDR  
- **Fast viz:** UMAPs, dot/violin plots with grouped markers  


