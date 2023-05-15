# NLP_Team_Synapse_Clickbait_Spoiler_Generation
The Webis Clickbait Spoiling Corpus 2022 (Webis-Clickbait-22) contains 5,000 spoiled clickbait posts crawled from Facebook, Reddit, and Twitter.
This corpus supports the task of clickbait spoiling, which deals with generating a short text that satisfies the curiosity induced by a clickbait post.
This dataset contains the clickbait posts and manually cleaned versions of the linked documents, and extracted spoilers for each clickbait post.
Additionally, the spoilers are categorized into three types: short phrase spoilers, longer passage spoilers, and multiple non-consecutive pieces of text.

## Overview

The dataset comes with predefined train/validation/test splits:

- [3,200 posts for training](training.jsonl)
- [800 posts for validation](validation.jsonl)


## Spoiler type classification

### Steps to execute- (Feature_based_classification(milestone2).ipynb,novel_feature_based_classification.ipynb, baseline_biLSTM.ipynb, novel_biLSTM.ipynb, baseline_BERT_classification.ipynb, novel_BERT_classification.ipynb)

* Open the notebook.
* Some packages require python version to be 3.9. To change it, Tools->Command Pallete-> Use Fallback runtime version
* Upload the train.jsonl and validation.jsonl to the notebook environment
* Run all the cells

## Question Answering
1. The code base has two differnt folders for Milestone 2 and Milestone 3 inside the Question Answering folder
2. To execute the baseline code, navigate to Milestone 2 folder,
  * Open the notebook
  * Upload the raw data from [https://github.com/trs-kaushik/NLP_Team_Synapse_Clickbait_Spoiler_Generation/tree/main/Data]
  * Run all the cells
  * Results and trained models would be stores in the drive
3. To execute the novel approach, navigate to Milestone 3 folder,
  * Either execute the Novel_Data_Preparation.ipynb notebook[https://github.com/trs-kaushik/NLP_Team_Synapse_Clickbait_Spoiler_Generation/blob/main/Question%20Answering/Milestone_2/Novel_Data_Preparation.ipynb] or use the   preprocessed data from [https://github.com/trs-kaushik/NLP_Team_Synapse_Clickbait_Spoiler_Generation/tree/main/Question%20Answering/Milestone_2/Processed_Data] for the below steps
  * To execute phrase spoiler generation model navigate to Question Answering/Milestone_2/Phrase_Spoiler_Generation
  * To execute passage spoiler generation model navigate to Question Answering/Milestone_2/Passage_Spoiler_Generation
  * Open the corresponding notebooks for BERT, RoBERTa, and DeBERTa
  * Upload the Processed Data
  * Run all the cells
  * Results and trained models would be stores in the drive

## Passage retrieval

### Steps to execute - (passage_retrieval.ipynb)
* Open the notebook
* Some packages require python version to be 3.9. To change it, Tools->Command Pallete-> Use Fallback runtime version
* Upload the train.jsonl and validation.jsonl to the notebook environment
* Run all the cells
