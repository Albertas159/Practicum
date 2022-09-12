# MCM PRACTICUM - The Blurble System

## Team

Albertas Ovodas

Théo Delettre

## Introduction

We investigate the effectivness of summerization models (BART,BERT,PEGUSUS and T5) with novels, with the goal of creating blurbs. This input source is drastically longer than previous litterature, which mainly explores the use of datasets based on shorter, factual, news articles. 
We create our own test datasets, by data mining/extracting information from Project Gutenberg, Wikipedia, and Goodreads.

## Instructions

Most of the code for this project has been done in Google Colab and can now be found in /src/. 
- Dataset_Genesis.ipynb Has all the code for creating the main datasets
- This Dataset is analized and trimmed in Data_Analysis.ipynb
- Various models are prepared and run on the dataset in the "Models and Results" folder
- Other files are self-explinatory and were made to better analyse and understand our results

## Programs/Technology Used
Python
  - Natural Language Processing
  - Named entity recognition
    - Spacy
    - NLTK
    - Flair
  - Hugging face Summerization Models with various finetunning
    - BART 
    - T5
    - BERT,
    - Pegasus 
  - Data minning/scraping
    - Wikipedia
    - Project gutenberg
    - Goodreeds
  - Evaluation Metrics
    - ROUGE
    - F1/Precision/Recall

Colaboration
  - google colab
  - Latex

## Learned about
- Encoders/Decoders
- Attention Mechanisms
- Transformers
- Pre Training
- Fine Tunning
- Evalutaion Metrics
- Data Scraping
- Machine Learning behind Summerizers

## Results and Analysis
All the results and in depth analysis of theory, model, disscusions and results can be found in /doc/Practicum_Report-Theo_Albert.pdf

Main Findings for summerizer:
![image](https://user-images.githubusercontent.com/100313005/189165968-921f96fa-b7c8-442e-a94a-6bef34c3a5ee.png)

Main Findings for NER:
![image](https://user-images.githubusercontent.com/100313005/189166164-b6cff926-8730-45e3-a3d4-c90ca5b5dcfc.png)


## DEMO

![image](https://user-images.githubusercontent.com/100313005/189165710-5e048ef0-2571-43d3-98df-55f44453f0f8.png)

