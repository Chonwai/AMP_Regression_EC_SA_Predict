# Project Title

A BERT-based Transfer Learning Approach for Predicting the Minimum Inhibitory Concentrations of Antimicrobial Peptides for Escherichia coli and Staphylococcus aureus

## Description

Antimicrobial peptides (AMPs) are a promising alternative for combating bacterial drug resistance. While current computer prediction models excel in binary classification of AMPs from squences, 
there is a lack of regression methods to accurately quantify AMP activity against specific bacteria, making the identification of highly potent AMPs a challenge. In this study, we proposed a 
deep learning model based on the fine-tuned Bidirectional Encoder Representations from Transformers (BERT) architecture to extract embedding features from input squences and predict minimum inhibitory concentrations (MICs) for target bacterial species. Using the transfer learning strategy, we built re gression models for Escherichia coli (EC) and Staphylococcus aureus (SA) using data curated from DBAASP.

## Getting Started

### Python packages

* torch==2.0.1+cu118
* biopython==1.81
* transformers==4.28.1
* tokenizers==0.13.3

### Predict squences (receive a fasta file and output a csv file)
* in the /predict/predict.py, change the variables (fasta_path, csv_path) to your own filename, run /predict/predict.py to predict pMIC values for input squences

## Acknowledgments

Inspiration, code snippets, etc.
* Elnaggar, Ahmed, Michael Heinzinger, Christian Dallago, Ghalia Rehawi, Yu Wang, Llion Jones, Tom Gibbs et al. "Prottrans: Toward understanding the language of life through self-supervised learning." IEEE transactions on pattern analysis and machine intelligence 44, no. 10 (2021): 7112-7127.
