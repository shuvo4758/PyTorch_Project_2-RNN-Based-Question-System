# PyTorch_Project_2-RNN-Based-Question-System

--RNN-Based Question Answering System--
This project implements a simple Question Answering system using a Recurrent Neural Network (RNN) built with PyTorch. The model is trained on a custom dataset of 100 unique question-answer pairs to learn the relationship between a question and its corresponding answer. The primary goal is to demonstrate the fundamentals of NLP preprocessing, vocabulary building, and sequence modeling with RNNs.

--Project Overview--
The system takes a natural language question as input and predicts a single-word answer. The process involves:
1.  Tokenization: Breaking down sentences into individual words.
2.  Vocabulary Building: Creating a unique vocabulary of all words from the dataset.
3.  Numericalization: Converting words into numerical indices based on the vocabulary.
4.  Modeling: Using an RNN to process the sequence of question words and predict the answer.
5.  Prediction: Returning a predicted answer or "I Don't know" if the model's confidence is low.
