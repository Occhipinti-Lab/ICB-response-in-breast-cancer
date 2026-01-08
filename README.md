# Metabolic coordination of glycolysis and N-linked glycosylation shapes immune checkpoint blockade responses in breast cancer

This repository contains the code, pipelines, and processed data used in the study “Metabolic coordination of glycolysis and N-linked glycosylation shapes immune checkpoint blockade responses in breast cancer.”
The project uses metabolic modelling to investigate metabolic reprogramming associated with immune checkpoint blockade (ICB) response

The primary objectives of this repository are to:

- Reconstruct genome-scale metabolic models (GSMMs) generate flux rates for bulk transcriptomic data in vitro and in vivo.
- Generate single-cell and spatial fluxomics using scFEA to characterise cell-type-specific metabolic reprogramming following ICB.

The data can be downloaded at : 
Repository Structure

```text
├── data/
│   ├── bulk/                # Bulk RNA-seq and metabolomics (mouse and cell line)
│   ├── single_cell/         # scRNA-seq data (human breast cancer, ICB-treated)
│   ├── spatial/             # Spatial transcriptomics and metabolomics
│   └── metadata/            # Sample annotations and clinical metadata
│
├── models/
│   ├── GSMM/                # Genome-scale metabolic models and constraints
│
└── README.md
```
