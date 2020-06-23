# Machine Learning Engineer Nanodegree
## Using NLP to Answer High-Priority Scientific Questions Related to COVID-19
### Covid-19 Open Research Dataset Challenge (CORD-19)
### Author: Joseph Cheng
### Created: June 15th, 2020
______________________________________________________________________________
<br>**Coding Language**: Python 3.6
<br>**IDE**: Jupyter Noteboos
<br>**Libraries used**: Please refer to the requirement.txt file
<br>**Download libaries command**: pip install -r requirements.txt

## Prerequisite
**Dataset**: Download the CORD-19 Dataset at CORD-19 Dataset at https://www.kaggle.com/allen-institute-for-ai/CORD-19-research-challenge/tasks?taskId=882
<br>**File name**: 551982_1230614_bundle_archive.zip
<br>**Key files** / folders used for the Project:

<br>**Meta data**                : metadata.csv
<br>**Priority Questions files** : Kaggle -> target_tables -> 2_relevant_factors
<br>**Research Paper Locations**    : document_parses -> pdf_json & pmc_json

## Files to run
Requires the Dataset to be downloaded
1. Data Exploratory and Cleansing of Labelled Data.iynb
2. Text Extraction from Labelled Literature.ipynb

Requires the pickle file **1_scoped_cat_lit.pkl** and **2_extracted_literature_data.pkl** from the first two jupyter notebook.
Source code already provided the pickle file for the ease of running the model.
<br>3. Search Engine using TFIDF.ipynb
<br>4. Supervised learning Model.ipynb
