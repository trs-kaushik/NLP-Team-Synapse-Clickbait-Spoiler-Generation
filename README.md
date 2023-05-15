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

## Passage retrieval

### Steps to execute - (passage_retrieval.ipynb)
* Open the notebook
* Some packages require python version to be 3.9. To change it, Tools->Command Pallete-> Use Fallback runtime version
* Upload the train.jsonl and validation.jsonl to the notebook environment
* Run all the cells
