# An Analysis of Turkish Political Election Manifestos and Training A Text Classifier with Bert

In this notebook a text classifier was trained for turkish political election manifestos. The goal is to develop a machine learning model that can accurately predict text data into classes (parties). The model is fine-tuned on a turkish bert model: BERTurk - BERT models for Turkish. https://github.com/stefan-it/turkish-bert

The dataset is created by turkish manifestos from 2002 to 2023 and three parties with diverse political positions (Right-wing, Centre-left to left-wing, and centre-left).

The dataset of manifesto sentences were labeled according to their parties and then tokenized with Bert tokenizer to obtain contexual tokens. These tokens were then passed through neural network layers to make predictions.

Parties in the dataset:
CHP (Republican People's Party)
AKP (Justice and Development Party)
HDP/BDP/Dem Parti (People's Democratic Party)

This project is submitted for the Computational Linguistics Course Final Project at Saarland University
