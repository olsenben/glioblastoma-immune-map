# Spatial Analysis of the Glioblastoma Immune Microenvironment

This project uses single-cell RNA-seq and spatial transcriptomics data to characterize immune infiltration and cell–cell interactions in the glioblastoma microenvironment. The goal is to map exhausted immune states, identify spatially localized immune niches, and explore interactions between tumor and immune cells.

## Objectives

- Identify immune cell subtypes (e.g. CD8+ T cells, TAMs) from scRNA-seq data.
- Map single-cell annotations onto spatial transcriptomics using integration tools.
- Detect spatially enriched immune zones and tissue architecture features.
- Analyze neighborhood interactions and immune exclusion patterns.
- Investigate ligand–receptor signaling between immune and tumor compartments.

## Data

**scRNA-seq**  
- Dataset: [GSE131928](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE131928)  
- Source: Neftel et al., *Cell*, 2019  
- Content: Single-cell transcriptomes from human glioblastoma samples

**Spatial Transcriptomics**  
- Dataset: [10X Visium Glioblastoma](https://www.10xgenomics.com/resources/datasets/glioblastoma-multiforme-1-standard-1-3-0)  
- Content: Spatial gene expression and H&E imaging of glioblastoma tissue

## Methods

- Preprocessing and clustering using `Scanpy`
- Spatial integration using `Tangram` or `Cell2Location`
- Spatial neighborhood analysis with `Squidpy`
- Ligand–receptor interaction analysis using `CellPhoneDB` or `NicheNet`
- Visualization of spatial domains, immune hotspots, and gene expression maps