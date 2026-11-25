---
project: "Gene Expression Imputation"
projectMembers:
  - chandulaj@eng.pdn.ac.lk
  - e19249@eng.pdn.ac.lk
  - e19408@eng.pdn.ac.lk
supervisors: []
researchArea: Generative AI
researchPillars: []
coverImage: ./cover_images/Gene_Expression_Imputation.jpg
---

**Single-cell RNA sequencing** (scRNA-seq) measures gene expression in thousands of individual cells, revealing cell types, cell states and how they change in development and disease. The data, however, are extremely sparse: only a small fraction of each cell's RNA is captured, so many genes that are actually expressed are recorded as zero. These **dropouts** blur the biological signal and weaken downstream analyses such as clustering, cell-type annotation and differential expression.

This project develops **generative models for gene expression imputation**, recovering each cell's likely expression profile from the genes that were observed. Because expression measurements are counts, we use **discrete diffusion**: the model learns to reverse a gradual corruption process defined directly on discrete values, rather than on continuous Gaussian noise, and restores missing entries step by step. The aim is imputation that fills the gaps while preserving the gene–gene relationships and cell-type structure that make the data biologically meaningful.

The project is part of MARC's wider research on [diffusion models](/projects/diffusion/).
