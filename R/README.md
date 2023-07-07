# CODE FOLDERS
This repository contains the code and data used for my bachelor's degree thesis in bioinformatics. The thesis focuses on exploring the role of long non-coding RNAs (lncRNAs) in medulloblastoma (MB), a malignant brain tumor primarily affecting children worldwide.

## Folders content

- **dbSNP**: Contains the scripts used for processing and analyzing genetic data downloaded from the dbSNP database. The code includes filtering, organizing, and creating plots related to known polymorphisms within a region of interest close to the genetic coordinates of three specific lncRNAs.

- **eQTLs**: This folder contains the code for extracting and analyzing expression quantitative trait loci (eQTLs) data from the Genotype-Tissue Expression (GTEx) project. The code includes filtering the eQTLs datasets, identifying relevant variants within the lncRNAs loci, and performing statistical analysis to gain insights about variation-gene associations.
- 
- **StructurePrediction**: This folder contains the scripts used for retrieving the lncRNA transcript, identifying the positions of SNPs within the transcript, and generating mutant transcripts by altering the nucleotides affected by the mutations. This serve as preprocessing steps before applying RNAfold structure prediction of the secondary structure of the lncRNA, with andwithout mutation.
