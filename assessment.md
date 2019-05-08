# Chemical Informatics

## Introduction
The assessment refers to the ‘Solubility Challenge’ as described in a couple of papers Llinas et al, 'Solubility Challenge:...', J. Chem. Inf. Model, 48, 2008, 1289-303 and Hopfinger et al, 'Findings of the Challenge...', J. Chem. Inf. Model, 49, 2009, 1–5

The objective will be to build a Quantitative Structure Property Relationship (QSPR) model for solubility using the descriptor sets calculated by the Dragon software package and evaluate the models you build.

## Outline

 1. Consider the rationale for splitting the molecules into training and test sets. Comment on the suitability (or otherwise) of the split provided. How would you check the validity of this split? What changes would you make?
 1. Import the training set into your notebook
 1. Think about what descriptors may be relevant in explaining or predicting solubility, and the potential issues that may arise in the choice of descriptors. Review the set of descriptors provided.
 1. Use RDKit, with the provided descriptors, to obtain a set of potentially useful descriptors to model solubility.
 1. Use the ideas from the lectures to build and optimize a multi-linear linear least squares regression (MLR) QSPR statistical model of the activities of the training set based on the descriptors you have. 
 1. Import the test set data and use your test set to check on the quality of the model(s) you produce. You may need to review your choice of descriptors in the light of the test results.
 1. You might try other modelling techniques e.g. PCA, PLS, neural networks, Random Forests.  How can you compare the results of the different models?

## Assessment Material

 1. A formal written report, length equivalent to about 3-4 A4 pages, including figures and references. You may wish to use the notebook system to make a reproducible document, or create a document on word processing software. If producing a notebook, please include both the `.ipynb` file, and a `.html` file.
 1. Data files
     1. Use your initiative here - the purpose of this is to provide the reader with as much supporting information as possible, so that they are able to reproduce your work. You should therefore think about the detail, organisation, and file formats you make available.
 
_Feel free to include README files with your work._

## Data Sets

The data sets required contained within the `data/raw` directory. The files are described as follows:
 - `training_subset.csv`: A subset of descriptors from the DRAGON software for the training set of molecules
 - `test_subset.csv`: As `training_subset`, for the test set
 - `dragon_molecular_descriptors.pdf`: A description of the provided descriptors

