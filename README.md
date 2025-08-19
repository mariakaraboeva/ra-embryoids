# ra-embryoids
Hello! Welcome to ra-embryoids. Here presented are Jupyter notebooks to help you perform single cell analysis in the embryoid (embryo model) system and reproduce my results!

This workflow has been utilised and optimised within the Master Thesis Project "Investigating the effect of metabolic perturbation on synthetic mouse embryos using scRNA-seq", Maria Karaboeva, 2025, Utrecht University. 

With this Python-based workflow you can perform barcode (droplet) filtering, quality control (QC), doublet simulations with Scrublet, data normalisation, dimensionality reduction and clustering, data integration and batch correction, cell type annotation, non-automatic reference mapping, differential expression (DE) analysis, enrichment analysis and compositional analysis within the scverse scanpy framework (with some input from scvi-tools) on single-cell RNA-seq data, according to recommended practices in single-cell analysis (Heumos et al., 2023).

Directory structure:

```bash
├── envs
│   ├── requirements.txt
│   ├── conda.txt
├── Figs_thesis
├── Figures
│   ├── Annotation
│   ├── Compositional
│   ├── Concatenation
│   ├── DE
│   ├── Diagnostic_Annotation
│   ├── Diagnostic_QC
│   ├── Doublet_QC
│   ├── Enrichment
│   ├── Filtering_QC
│   ├── Gene_Filtering
│   ├── Integration
│   ├── Normalisation_Clustering
│   ├── Preliminary_Annotation
│   └── Raw_Filtering
├── Tables
│   ├── Annotation_Markers
│   ├── Compositional
│   ├── DE
│   └── Enrichment
```
1. envs contains the requirements for the two environments used in the project. scvi-tools and sccoda libraries are only installed in the pip environment and sccoda is only available through pip.
2. Figs_thesis contains the complete, assembled figures as present in the thesis text.
3. Figures contains all figures generated at the workflow steps.
4. Tables contains all data tables results generated during the workflow steps including snapshots from DAVID webpage output (Gene Ontology Enrichment results)

References:
1. Heumos, L., Schaar, A.C., Lance, C. et al. Best practices for single-cell analysis across modalities. Nat Rev Genet 24, 550–572 (2023). https://doi.org/10.1038/s41576-023-00586-w
2. Samuel L. Wolock, Romain Lopez, Allon M. Klein, Scrublet: Computational Identification of Cell Doublets in Single-Cell Transcriptomic Data, Cell Systems, Volume 8, Issue 4, 2019, Pages 281-291.e9, ISSN 2405-4712. https://doi.org/10.1016/j.cels.2018.11.005.
3. Gayoso, A., Lopez, R., Xing, G. et al. A Python library for probabilistic analysis of single-cell omics data. Nat Biotechnol 40, 163–166 (2022). https://doi.org/10.1038/s41587-021-01206-w
4. Wolf, F., Angerer, P. & Theis, F. SCANPY: large-scale single-cell gene expression data analysis. Genome Biol 19, 15 (2018). https://doi.org/10.1186/s13059-017-1382-0
5. Virshup, I., Bredikhin, D., Heumos, L. et al. The scverse project provides a computational ecosystem for single-cell omics data analysis. Nat Biotechnol 41, 604–606 (2023). https://doi.org/10.1038/s41587-023-01733-8
6. Büttner, M., Ostner, J., Müller, C.L. et al. scCODA is a Bayesian model for compositional single-cell data analysis. Nat Commun 12, 6876 (2021). https://doi.org/10.1038/s41467-021-27150-6
7. Ashburner, M., Ball, C., Blake, J. et al. Gene Ontology: tool for the unification of biology. Nat Genet 25, 25–29 (2000). https://doi.org/10.1038/75556
8. Brad T Sherman, Ming Hao, Ju Qiu, Xiaoli Jiao, Michael W Baseler, H Clifford Lane, Tomozumi Imamichi, Weizhong Chang, DAVID: a web server for functional enrichment analysis and functional annotation of gene lists (2021 update), Nucleic Acids Research, Volume 50, Issue W1, 5 July 2022, Pages W216–W221, https://doi.org/10.1093/nar/gkac194








