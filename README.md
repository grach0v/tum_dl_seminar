# tum_dl_seminar


# Modalities 
- ATAC (Assay for Transposase-Accessible Chromatin):
  - ATAC measures how accessible different regions of DNA are in a cell.
  - Accessible regions are where the cell’s machinery can interact with DNA, such as areas where genes are actively being used (turned on).
  - Think of it as a way to map which parts of the DNA are "open for business" and potentially active in a cell.

- GEX (Gene Expression):
  - GEX refers to measuring how much RNA is being produced from genes.
  - RNA is like a messenger that carries the instructions from DNA to make proteins.
  - Measuring RNA tells us which genes are active and how active they are in a particular cell.

- ADT (Antibody-Derived Tags):
  - ADT measures specific proteins on the surface or inside a cell using antibodies.
  - Proteins are the functional molecules that do most of the work in cells, so this gives insight into the cell's behavior or identity.
  - It's like checking what "tools" a cell is using at the moment.


# Datasets 
- CITE-seq Dataset (cite_BMMC_processed.h5ad.gz):
   - Modality: Focuses on RNA (GEX) and protein (ADT) data.
   - Technology Used: CITE-seq (Cellular Indexing of Transcriptomes and Epitopes by sequencing).
      - Combines RNA sequencing with protein measurement using antibody-derived tags.
   - Data Contents:
      - RNA data (GEX): Transcript counts for thousands of genes.
      - Protein data (ADT): Protein abundances for hundreds of markers.
   - Use Case: Ideal for studying relationships between RNA expression and corresponding protein levels.

- Multiome Dataset (multiome_BMMC_processed.h5ad.gz):
   - Modality: Focuses on RNA (GEX) and chromatin accessibility (ATAC) data.
   - Technology Used: Multiome (joint profiling of RNA and ATAC).
      - Measures RNA expression and chromatin accessibility in the same cells.
   - Data Contents:
      - RNA data (GEX): Transcript counts for thousands of genes.
      - ATAC data: Accessibility scores for thousands of genomic regions.
   - Use Case: Ideal for understanding how chromatin accessibility (DNA regulation) influences RNA expression.