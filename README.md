# Osteosarcoma scRNA-seq Analysis

Analysis of human primary osteosarcoma single-cell RNA sequencing data from the OsteoCAR multi-species atlas (Budhathoki et al. 2026).

## Data
- Source: [Figshare](https://figshare.com/articles/dataset/OsteoCAR_A_multi-species_single-cell_atlas_of_primary_and_metastatic_osteosarcoma/31029559)
- 152,770 cells from human primary osteosarcoma patients
- Cell types annotated across 4 hierarchical levels using SingleR

## Contents
- `analysis.R` — script for loading data and generating UMAP visualizations
- `patient_prim_umaps.pdf` — UMAP plots colored by cell type annotation levels

## Cell Populations
- **Level 0**: Tumor vs Host
- **Level 1**: Broad types (Tumor, Myeloid, T cells, Mesenchymal, Endothelial)
- **Level 2**: ~20 populations including TAMs, CAFs, NK cells, DC subtypes
- **Level 3**: ~50 fine-grained subtypes

## Reference
Budhathoki et al. 2026. Integrative Single-cell and Spatial Transcriptomic Analysis of Osteosarcoma. https://doi.org/10.64898/2026.01.13.698472
