# NLP_Team_Synapse_Clickbait_Spoiler_Generation

## Contributors - 
* **Kaushik Kumar TRS**
* **Swaminathan Venkataraman**
* **Nikitha Sadananda**

## Summary
The Webis Clickbait Spoiling Corpus 2022 (Webis-Clickbait-22) contains 5,000 spoiled clickbait posts crawled from Facebook, Reddit, and Twitter.
This corpus supports the task of clickbait spoiling, which deals with generating a short text that satisfies the curiosity induced by a clickbait post.
This dataset contains the clickbait posts and manually cleaned versions of the linked documents, and extracted spoilers for each clickbait post.
Additionally, the spoilers are categorized into three types: short phrase spoilers, longer passage spoilers, and multiple non-consecutive pieces of text.

## Overview

The dataset comes with predefined train/validation/test splits:

- [3,200 posts for training](training.jsonl)
- [800 posts for validation](validation.jsonl)


## Spoiler type classification
1. The code has three different folders for feture based classification, neural based classification and transformer based classification.
2. To execute the feature based classification folder:
  * navigate to Feature_based_classification(milestone2).ipynb for baseline code.
  * navigate to novel_feature_based_classification.ipynb for milestone-3 novel approach.
3. To execute the neural based classification folder:
  * navigate to baseline_biLSTM.ipynb for baseline code of milestone-2
  * navigate to novel_biLSTM.ipynb for milestone-3 novel approach.
4. To execute the transformer based classification:
  * navigate to baseline_BERT_classification.ipynb for baseline code of milestone-2.
  * navaigate to novel_BERT_classification.ipynb for novel approach of milestone-3.

### Steps to execute the notebook files- 
* Open the notebook.
* Some packages require python version to be 3.9. To change it, Tools->Command Pallete-> Use Fallback runtime version
* Upload the train.jsonl and validation.jsonl to the notebook environment
* Run all the cells


## Question Answering
1. The code base has two different folders for Milestone 2 and Milestone 3 inside the Question Answering folder
2. To execute the baseline code, navigate to Milestone 2 folder,
  * Open the respective notebooks for BERT, RoBERTa, and DeBERTa
  * Upload the raw data from [https://github.com/trs-kaushik/NLP_Team_Synapse_Clickbait_Spoiler_Generation/tree/main/Data]
  * Run all the cells
  * Results and trained models would be stored in the drive
3. To execute the novel approach, navigate to Milestone 3 folder,
  * Either execute the Novel_Data_Preparation.ipynb notebook[https://github.com/trs-kaushik/NLP_Team_Synapse_Clickbait_Spoiler_Generation/blob/main/Question%20Answering/Milestone_3/Novel_Data_Preparation.ipynb] or use the   preprocessed data from [https://github.com/trs-kaushik/NLP_Team_Synapse_Clickbait_Spoiler_Generation/tree/main/Question%20Answering/Milestone_3/Processed_Data] for the below steps
  * To execute phrase spoiler generation model navigate to Question Answering/Milestone_3/Phrase_Spoiler_Generation
  * To execute passage spoiler generation model navigate to Question Answering/Milestone_3/Passage_Spoiler_Generation
  * Open the corresponding notebooks for BERT, RoBERTa, and DeBERTa
  * Upload the Processed Data
  * Run all the cells
  * Results and trained models would be stores in the drive
4. To execute the end to end model, navigate to [https://github.com/trs-kaushik/NLP_Team_Synapse_Clickbait_Spoiler_Generation/tree/main/Question%20Answering/Milestone_3/End_to_End_Pipeline]
  * Due to space constraint, we were not able to upload the saved model
  * Execute the Milestone 3 codes, Phrase level DeBERTa and Passage level DeBERTa
  * Verify if the model has been saved in the drive
  * Open the End to End pipeline script
  * Execute the RoBERTa classifier or take the already predicted data from [https://github.com/trs-kaushik/NLP_Team_Synapse_Clickbait_Spoiler_Generation/blob/main/Question%20Answering/Milestone_3/Processed_Data/RoBERTa_classified_validation_dataset.jsonl] and upload into the local directly of the end_to_end pipeline script
  * Run all the cells

## Passage retrieval

### Steps to execute - (passage_retrieval.ipynb)
* Open the notebook
* Some packages require python version to be 3.9. To change it, Tools->Command Pallete-> Use Fallback runtime version
* Upload the train.jsonl and validation.jsonl to the notebook environment
* Run all the cells
