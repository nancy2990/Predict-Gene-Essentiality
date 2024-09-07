# Predicting gene essentiality

## Introduction

This repository contains code for predicting gene essentiality using machine learning models. Gene essentiality prediction is a critical task in molecular biology and genetics, as it helps in identifying genes that are crucial for the survival of an organism. This README provides an overview of the project structure, data sources, and instructions for running the code.

## Project Structure

The project structure is organized as follows:

- `data/`: Contains the raw data used for training and testing the models and data-pre-processing for feature generation.
- `model/`: Contains the trained machine learning models.
- `E.coli/`: Contains the source code for E coli's model training, and evaluation.
- `Mycoplasma/`: Contains the source code for Mycoplasma's predicted threshold, model training, and evaluation.
- `Staphylococcus/`: Contains the source code for Staphylococcus's model training, and evaluation.
- `Results/`: Contains the results obtained from model evaluation.

## Data Sources

The data used in this project is sourced from publicly available databases and repositories. These include:

- [NCBI Gene Expression Omnibus (GEO)](https://www.ncbi.nlm.nih.gov/geo/): Provides gene expression data.
- [AureoWiki](https://aureowiki.med.uni-greifswald.de/Main_Page): Provides Staphylococcus data.
- [Database of Essential Genes (DEG) ](https://tubic.org/deg/public/index.php): Provides E. coli sequence data.
- [Database of Predicted Essential Genes (pDEG)](http://origin.tubic.org/pdeg/index.html) : Provides Mycoplasma sequence data.

## Requirements

- Python 3
- Required Python packages listed in `requirements.txt`. Install them using `pip install -r requirements.txt`.

## Usage

1. Clone the repository: `git clone https://github.com/your_username/gene-essentiality-prediction.git`
2. Navigate to the project directory: `cd gene-essentiality-prediction`
3. Prepare the data:
   - Download raw data from the provided sources and place them in the `data/` directory.
   - Preprocess the data using the scripts in the `data/generate feature` directory.
4. Train the models:
   - Run the model training scripts in the `E. coli` `Mycoplasma` `Staphylococcus` directory.
5. Evaluate the models:
   - Run the model evaluation scripts in the ``E. coli` `Mycoplasma` `Staphylococcus` ` directory.
6. View the results:
   - Results will be saved in the `Results/` directory.
