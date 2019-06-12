# pancreatic-endocrinogenesis
This repository contains all scripts to reproduce the results of the single-cell data from:  
A. Bastidas-Ponce, S. Tritschler et al., "Comprehensive single cell mRNA profiling reveals a detailed roadmap for pancreatic endocrinogenesis", Development, 2019

The notebooks contain code for the following analyses:
- scRNA_seq_qc_preprocessing.ipynb  -->  preprocessing and filtering steps.
- scRNA_seq_doublet_detection.ipynb  -->  doublet score calculation.
- scRNA_scRNA_seq_main_analysis.ipynb  -->  main analyses to reproduce all results.
- scRNA_seq_RNAvelocity_estimation.ipynb  -->  RNA velocity estimation

Raw data has been deposited in GEO under accession number GSE132188. 

For further analyses processed and fully annotated AnnData objects are provided here (adata.h5ad and adata_hvg.h5ad). Load the adata.h5ad into a cellxgene browser for visualization or into a python-session for additional analyses using scanpy.

Note that the analysis was done with scanpy v1.3.2. Some functions have changed in newer versions of scanpy. For other package versions please consult the notebook or the methods in the supplementary information of the manuscript. Numeric results can vary depending on package versions.

If the materials in this repo are of use to you, please consider citing the above publication.
