# Assignment 03 - Comparison of ensemble approaches on gene expression data

Utilizes GTEx RNA seq data to compare ensemble models to predict age and tissue of origin for samples.

## Overview
- Dimensionality reduction
    - PCA & UMAP

- Ensemble model to predict tissue
    - model 1 FINSIH
    - model 2 FINISH
    
- Ensemble model to predict age
    - model FINSIH
    - blood samples only

## Environment set-up

Run ```conda env create -f environment.yml``` to create the environment 
<br> and ```conda activate cu-cpbs-7602``` to activate it

## Data

Data is accessed online.

- GTEx_Analysis_2017-06-05_v8_RNASeQCv1.1.9_gene_tpm.gct.gz
    - gene transcripts per million (TPMs)
- GTEx_Analysis_v8_Annotations_SampleAttributesDS.txt
    - metadata; sample annotations
- GTEx_Analysis_v8_Annotations_SubjectPhenotypesDS.txt
    - metadata; subject phenotype

## Usage

Run ```dimensionality_reduction.ipynb``` first, then run either ```ensemble_age_prediction.ipynb``` or ```ensemble_tissue_prediction.ipynb``` in any order.

## Author
@emilyekstrum
<br> emily.ekstrum@cuanschutz.edu