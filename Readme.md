# Chemical Informatics
Lennart Gundelach, 2019, TMCS Oxford
Gundelachlennart@gmail.com

## Introduction
As taken from assginment.md: 

The assessment refers to the ‘Solubility Challenge’ as described in a couple of papers Llinas et al, 'Solubility Challenge:...', J. Chem. Inf. Model, 48, 2008, 1289-303 and Hopfinger et al, 'Findings of the Challenge...', J. Chem. Inf. Model, 49, 2009, 1–5

The objective will be to build a Quantitative Structure Property Relationship (QSPR) model for solubility using the descriptor sets calculated by the Dragon software package and evaluate the models you build.

## Notebook
All work is presented in the ipython notebook ChemInfo_SolublityChallenge in the /Notebook directory. When Working with the notebook, the code cells should initially be executed in order, to ensure all necessary variable for later calcultions have been initialized. The notebook is also provided with all cells executed in HTML format for convenient viewing.  

## Data Sets

The data sets required contained within the `data/raw` directory. The files are described as follows:
 - `training_subset.csv`: A subset of descriptors from the DRAGON software for the training set of molecules
 - `test_subset.csv`: As `training_subset`, for the test set
 - `dragon_molecular_descriptors.pdf`: A description of the provided descriptors
 - `processed/test_subset.csv`: Processed test set 

