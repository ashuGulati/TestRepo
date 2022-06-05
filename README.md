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

|accuracy          |          |precision       |recall           |f1-score         |support|
|------------------|------------|------------------|------------------|------------------|---------|
|0.8967197141929197|macro avg   |0.9025603216581297|0.896744921744922 |0.8968213713372181|3079     |
|                  |weighted avg|0.9025524395708827|0.8967197141929197|0.8968040999410952|3079     |
|                  |micro avg   |0.8967197141929197|0.8967197141929197|0.8967197141929197|3079     |




## Online Repository link

* [DataRepository](https://www.kaggle.com/datasets) - Link to the data repository.
