# Assignment 2: Linear predictors using gene expression

Utilizes GTEx RNA seq data to fit multiple linear regression and logistic regression models to predict tissue type and sex.

## Overview
- Multiple linear regression
    - predicts tissue type adjusting for age and sex using gene expression data from blood and brain samples
- Logisitic regression
    - predicts sex using gene expression data from blood samples

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

Run the notebook ```assignment02_notebook.ipynb``` in sequential order.

## Author
@emilyekstrum
<br> emily.ekstrum@cuanschutz.edu