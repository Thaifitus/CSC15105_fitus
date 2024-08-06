# Introduction to Question Answering System
This repository is about my work in two projects of **Text Mining and Application (CSC15105)** course. The work started from Feb. 2024 to May 2024 but completed in five weeks. 

# Introduction
The project is about question answering system which is organized into two problems: (1) Sentence similarity, (2) Question answering. In each problem, we are given the corresponding dataset and required to:
1. EDA
2. Fine-tune model
3. Survey the model with various hyperparameters
4. Write report, make slide and present in class

# Task list
My work in each problem:

1. Sentence similarity
* EDA: load the data to Pandas DataFrame and implement **analysis** (rows, columns, duplication, length distribution, label distribution).
* Survey model: load and **retrain** pre-trained model using sentence_transformers API with **cosine similarity**; evaluate model using **accuracy, recall, precision, F1** by scikit-learn.
2. Question answering
* Study data structure and research PhoBERT theoretically.
3. I made slides 30 - 37 in `Slide_sentence_similarity.pdf`; 2 - 8 in `Slide_question_answering.pdf`.

# Reproduce result
To reproduce results, upload notebook files (.ipynb) to Google Colab (please provide item(s) if required) and `Run all` cells.
