# NLP_Team_Synapse_Clickbait_Spoiler_Generation
The Webis Clickbait Spoiling Corpus 2022 (Webis-Clickbait-22) contains 5,000 spoiled clickbait posts crawled from Facebook, Reddit, and Twitter.
This corpus supports the task of clickbait spoiling, which deals with generating a short text that satisfies the curiosity induced by a clickbait post.
This dataset contains the clickbait posts and manually cleaned versions of the linked documents, and extracted spoilers for each clickbait post.
Additionally, the spoilers are categorized into three types: short phrase spoilers, longer passage spoilers, and multiple non-consecutive pieces of text.

## Overview

The dataset comes with predefined train/validation/test splits:

- [3,200 posts for training](training.jsonl)
- [800 posts for validation](validation.jsonl)

The data folder contains train.jsonl and validation.jsonl. 

The spoiler type classification is loaded with train.jsonl and validation.jsonl data. It contains the following  spoiler type classification:

-Feature_based_classification: The ipynb codebase, with milestone2 and novel_feature based classification(milestone3)

-Neural_based_classification: The ipynb codebase with baseline_bilstm(milestone2) and novel_bilstm(milestone3).

-Transformer_based_classification: The ipynb codebase with baseline_bert_classification(milestone2) and novel_bert_classification(milestone3).

The passage retrieval folder consists of ipynb notebook of passage retrieval codebase. 

## Spoiler classification

### Steps to execute (baseline_biLSTM.ipynb, novel_biLSTM.ipynb, baseline_BERT_classification.ipynb, novel_BERT_classification.ipynb)

* Open the notebook
* Some packages require python version to be 3.9. To change it, Tools->Command Pallete-> Use Fallback runtime version
* Upload the train.jsonl and validation.jsonl to the notebook environment
* Run all the cells

## Passage retrieval

### Steps to execute - (passage_retrieval.ipynb)
* Open the notebook
* Some packages require python version to be 3.9. To change it, Tools->Command Pallete-> Use Fallback runtime version
* Upload the train.jsonl and validation.jsonl to the notebook environment
* Run all the cells
