# NLP Project – Central Bank Communication as Alternative Data

This repository contains the code and report for my ENSAE NLP course project.

## Project title

**Central Bank Communication as Alternative Data: Topic Modeling Study of BIS Speeches and Temporal Evolution**

## Author

Maria Abi Rizk  
ENSAE Paris – NLP Project  
April 2026

## Project objective

This project studies whether central bank speeches can be transformed into interpretable textual indicators using Natural Language Processing methods.

The analysis is based on the BIS central bank speeches dataset, available on Hugging Face under the name:

`samchain/bis_central_bank_speeches`

The main research question is:

> Can unsupervised NLP methods extract interpretable topics from central bank speeches, how do these topics evolve over time, and can a simple lexical score capture changes in hawkish-dovish communication?

## Repository structure

```text
.
├── 01_Data_Analysis_EDA_CBF.ipynb
├── 02_Preprocessing_for_TopicModeling_CBF.ipynb
├── 03_NMF_Topic_Modeling_CBF.ipynb
├── 04_LDA_Topic_Modeling_CBF.ipynb
├── 05_BERTopic_Topic_Modeling_CBF.ipynb
├── 06_Hawkish_Dovish_Tone_BIS_CBF.ipynb
├── NLP_Report_Maria_ABIRIZK_CentralBanks.pdf
└── README.md

Notebooks
01_Data_Analysis_EDA_CBF.ipynb

Exploratory data analysis of the BIS speeches corpus.
This notebook describes the raw dataset, missing values, duplicate texts, speech length distribution, yearly coverage, and central bank representation.

02_Preprocessing_for_TopicModeling_CBF.ipynb

Text cleaning and preprocessing pipeline.
The notebook removes missing and low-quality texts, filters short speeches, applies normalization, tokenization, lemmatization, part-of-speech filtering, and creates the final modeling corpus.

03_NMF_Topic_Modeling_CBF.ipynb

Topic modeling with TF-IDF and Non-negative Matrix Factorization.
This notebook estimates several NMF models, compares candidate numbers of topics, selects the final model, interprets the topics, and studies their evolution over time.

04_LDA_Topic_Modeling_CBF.ipynb

Topic modeling with Latent Dirichlet Allocation.
This notebook uses count-based document-term matrices, estimates LDA models for several topic numbers, compares perplexity, log-likelihood and coherence, and analyzes temporal topic patterns.

05_BERTopic_Topic_Modeling_CBF.ipynb

Embedding-based topic modeling with BERTopic.
This notebook uses sentence-transformer embeddings, UMAP dimensionality reduction, HDBSCAN clustering, and class-based TF-IDF topic representations.

06_Hawkish_Dovish_Tone_BIS_CBF.ipynb

Exploratory hawkish-dovish tone analysis.
This notebook builds a dictionary-based lexical score measuring the relative frequency of restrictive versus accommodative monetary-policy vocabulary.

Report

The final report is available in this repository:

NLP_Report_Maria_ABIRIZK_CentralBanksF.pdf
