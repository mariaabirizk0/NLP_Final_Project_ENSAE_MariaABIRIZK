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
