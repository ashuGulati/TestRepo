# About Repository

**agents-datasets** repository contains a collection of all the datasets and models that have been trained using RASA NLU.

## About datasets and training methodology

### Dataset
We have used publicly available datasets and trained them using Rasa NLU in order to create individual agent models. 

### Rasa NLU
Rasa is an open source machine learning framework for automated text and voice-based conversations. Understand messages, hold conversations, and connect to messaging channels and APIs.
The goal of NLU (Natural Language Understanding) is to extract structured information from user messages. This usually includes the user's intent and any entities their message contains. 
For further details, visit [Rasa Docs](https://rasa.com/docs/rasa/).


Project Organization
------------
```bash
  ├───airline
  ├───airline_with_split
  │   ├───results
  │   └───train_test_split
  ├───banking77
  │   ├───data
  │   └───results
  ├───banking_RASAHQ
  │   ├───results
  │   └───train_test_split
  ├───hotel
  │   ├───results
  │   └───train_test_split
  └───restaurant
      ├───results
      └───train_test_split
```

--------

## Model Report

Agent Name     |  Accuracy  |  Precision  | Recall  |  F1-Score  |  Intent Count
-------- | -------- | -------- | -------- | -------- | ----
Banking | 0.896 | 

|accuracy|Banking      |precision|recall|f1-score|support|
|--------|------------|----------------|------------|--------------|--------------|
|0.897   |macro avg   |0.903           |0.897       |0.897         |3079          |
|        |weighted avg|0.903           |0.897       |0.897         |3079          |
|        |micro avg   |0.897           |0.897       |0.897         |3079          |



|accuracy|Airline      |precision|recall|f1-score|support|
|--------|------------|----------------|------------|--------------|--------------|
|0.955   |macro avg   |0.661           |0.556       |0.584         |1391          |
|        |weighted avg|0.952           |0.955       |0.951         |1391          |
|        |micro avg   |0.955           |0.955       |0.955         |1391          |




## Online Repository link
[change1](test/RemoteFile.md#change1)
* [DataRepository](https://www.kaggle.com/datasets) - Link to the data repository.
