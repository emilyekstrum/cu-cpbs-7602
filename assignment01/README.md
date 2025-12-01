# Assignment 01

## Overview
This module uses DBSCAN and spectral clustering to cluster gene expression samples (TPM) based on their tissue of origin.


## Environment set-up

Run ```conda env create -f environment.yml``` to create the environment 
<br> and ```conda activate cu-cpbs-7602``` to activate it


## Data

Data can be accessed from the provided zip files and extracted for usage or can be downloaded from GTEx site directly
- to use zipped data, extract GTEx_Analysis_2017-06-05_v8_RNASeQCv1.1.9_gene_tpm.gct.gz.zip
- to download from GTEx site, download GTEx_Analysis_2017-06-05_v8_RNASeQCv1.1.9_gene_tpm.gct.gz AND file from https://gtexportal.org/home/downloads/adult-gtex/bulk_tissue_expression 


## Usage

Run the notebooks in the following order and save intermediate files to the current working directory: <br> 
    1. data_preprocessing.ipynb <br>
    2. cluster_analysis.ipynb <br>
    3. cluster_evaluation_and_interpretation.ipynb


## Author
@emilyekstrum
<br> emily.ekstrum@cuanschutz.edu