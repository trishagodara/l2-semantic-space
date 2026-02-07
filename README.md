# Exploring the Semantic Space of Second Language Learners
## Overview
This repository includes the main classification and feature filteration code used in the paper "Exploring the Semantic Space of Second Language Learners" by Trisha Godara, Rui He, Wolfram Hinzen, and Yan Cong.

## Data
The full French LANGSNAP dataset used can be found here: https://talkbank.org/slabank/access/French/LANGSNAP.html

For each task, content for each participant was cleaned and concatenated into a single paragraph for feature extraction. 

## Files
* **shap_analysis.ipynb**: This file contains the main feature filteration and classification pipeline. The input file for this is a CSV file with the extracted semantic space features. The Python notebook walks through the process, starting with feature reduction, followed by the classification tasks, and concluding with SHAP analysis to identify each model's top contributing features.

* **hyperparameter_tuning.ipynb**: Here we share the various hyperparameters we explored using cross validation for future researchers to investigate and reproduce.

## Contact
For any questions or concerns, please contact tgodara@purdue.edu.