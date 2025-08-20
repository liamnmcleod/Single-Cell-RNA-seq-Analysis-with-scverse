# Single-Cell-RNA-seq-Analysis-with-scverse
scRNA and snRNA-seq workflows with scverse tools (Scanpy + scvi-tools) integrated with PyTorch

Reproducible single-cell RNA-seq analysis using the scverse ecosystem  
(Scanpy, scvi-tools, anndata) with PyTorch-backed variational models.
From raw counts to annotated clusters, differential expression, and clean figures.


## Features
- **QC & filtering:** mitochondrial/ribosomal metrics, doublet flag support  
- **Normalization:** log1p or scvi-tools normalized layers  
- **Batch integration:** **scVI** latent space (`X_scVI`) — runs on CPU or **GPU via PyTorch**  
- **Clustering & UMAP:** neighborhood graph, Leiden/UMAP  
- **Automated annotation:** marker panels + per-cluster scoring  
- **Differential expression:** `model.differential_expression(...)` with FDR  
- **Fast viz:** UMAPs, dot/violin plots with grouped markers  


