# PFam-dataset

This project aims to solve the Kaggle challenge : https://www.kaggle.com/datasets/googleai/pfam-seed-random-split, which provides the dataset.

## Problem description
This project uses data based on the PFam dataset. These data are used for training a model and predicting the function of protein domains.

Domains are functional sub-parts of proteins; much like images in ImageNet are pre segmented to
contain exactly one object class, this data is presegmented to contain exactly and only one
domain.

The purpose of the dataset is to repose the PFam seed dataset as a multiclass classification
machine learning task.

The task is: given the amino acid sequence of the protein domain, predict which class it belongs
to. There are about 1 million training examples, and 18,000 output classes.

## Method
In the notebook, I performed :

- Data Analysis
- Explanation of my choices concerning models
- Two experimental parts : one with a restrictive dataset, the other using representation learning.
- Results & Summary
 
