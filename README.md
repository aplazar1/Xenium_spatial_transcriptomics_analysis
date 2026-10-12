
# Xenium Spatial Transcriptomics Analysis
An end-to-end spatial transcriptomics analysis of
10x Genomics Xenium human kidney tissue.

## Analysis

- Transcript-level quality control
- RNA normalization and Leiden clustering
- RNA-based cell-type annotation
- Spatially variable gene analysis
- Cell neighborhood enrichment
- Morphology and RNA concordance

## Tools

Python | Scanpy | Squidpy | AnnData | Zarr | Matplotlib


## Explore the Analysis

[View the Complete Xenium Analysis](https://aplazar1.github.io/Xenium_spatial_transcriptomics_analysis/)


[[View the Jupyter notebook](notebooks/Xenium_analysis (4).ipynb)](https://github.com/aplazar1/Xenium_spatial_transcriptomics_analysis/blob/main/Xenium_analysis%20(4).ipynb)

## Dataset Description

This project analyzes a publicly available **10x Genomics Xenium In Situ spatial transcriptomics dataset** generated from formalin-fixed, paraffin-embedded (FFPE) human kidney tissue.

The dataset combines high-resolution, targeted RNA measurements with tissue morphology, enabling the characterization of cellular heterogeneity, spatial gene expression patterns, and tissue organization at single-cell resolution.

### Data modalities

- **Spatial transcriptomics:** Transcript-level gene expression measurements with spatial coordinates and cell assignments.
- **Cell-level expression:** A gene-by-cell count matrix representing transcript abundance across segmented cells.
- **Cell segmentation:** Cell and nuclear boundaries, centroid coordinates, and morphological measurements.
- **Tissue imaging:** DAPI nuclear staining and corresponding H&E histology for morphological interpretation and spatial alignment.
- **Protein panel metadata:** Information describing the targeted protein assay panel, where available.

### Dataset characteristics

| Feature | Description |
|---|---|
| Technology | 10x Genomics Xenium In Situ |
| Tissue | Human kidney |
| Sample preparation | FFPE |
| Resolution | Single-cell and transcript-level |
| Gene panel | 405 genes represented in the expression matrix |
| Cell count | Approximately 460,000 segmented cells |
| Spatial information | Transcript coordinates, cell centroids, and segmentation boundaries |
| Imaging | DAPI morphology and H&E histology |
| Primary analysis framework | Python, Scanpy, AnnData |

### Scientific objectives

The analysis aims to characterize tissue cellular composition and spatial organization through transcript-level quality control, RNA-based cell-type annotation, spatially variable gene identification, and cell-neighborhood enrichment analysis.

By integrating gene expression with spatial coordinates and tissue morphology, the project provides an end-to-end workflow for investigating cellular heterogeneity and spatial relationships in human kidney tissue.

### Data source

**Provider:** 10x Genomics

**Dataset:** Xenium V1 Human Kidney FFPE Protein

**Data portal:** https://www.10xgenomics.com/datasets

The original dataset is available through 10x Genomics. Large raw imaging and transcriptomic data files are not redistributed in this repository.

## Reproducibility

See environment.yml for the computational environment.
EOF
