# Parkinsons-Families-Project

The Parkinson’s Families Project is a UK-wide study aimed at identifying genetic variation associated with familial and early-onset Parkinson's disease (PD). We recruited individuals with a clinical diagnosis of PD and age at motor symptom onset ≤ 45 years and/or a family history of PD in up to third-degree relatives. We analysed DNA samples with a combination of single nucleotide polymorphism (SNP) array genotyping, multiplex ligation-dependent probe amplification (MLPA), and whole-genome sequencing (WGS). We investigated the association between identified pathogenic mutations and demographic and clinical factors such as age at motor symptom onset, family history, motor symptoms (MDS-UPDRS) and cognitive performance (MoCA). Here we present the code used to perform all statistical analyses included in the manuscript.

The following files are necessary to run the code (available to download from https://doi.org/10.5281/zenodo.12549399):
1. PFP_data.csv (clinical and genetic data to run the statistical analyses); a data dictionary is also available that describes each variable.
2. PFP_PRS_model1_normalised.csv (z-transformed PRS, phenotype and covariates to run the PRS analysis)
3. PFP_PRS_model2_normalised.csv (z-transformed PRS, phenotype and covariates to run the PRS analysis)

Polygenic risk scores (PRS) and principal components (PCs) are provided in the files above, so it is unecessary to re-generate them from the raw genetic data. However, the SNP array genotyping data is available through EGA and we have included the code that was used to QC and impute the plink binary files. We have also included the steps to calculate and normalise the PRS, as well as the steps to lift the genome build and run Genotools for genetic ancestry determination (which is provided in the file PFP_data.csv).   

How to cite this material: 10.5281/zenodo.12552036
