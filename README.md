## Pathway Enrichment Analysis

Pathway enrichment was performed using Enrichr in September 2026.

- Input: 28 gene-symbol entries derived from the 25 most significant platform probes.
- Direction: Upregulated and downregulated entries were combined.
- Background: Enrichr default background; the 8,746 array-assayed genes were not used as a custom background.
- Libraries:
  - KEGG 2026
  - Reactome Pathways 2024
  - MSigDB Hallmark 2020
- Statistical framework: Fisher's exact/hypergeometric testing with Benjamini-Hochberg adjustment.
- Limitation: Because the input was small, direction-mixed, and used a non-custom background, results are exploratory and do not demonstrate pathway activation or inhibition.
