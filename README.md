# English-to-Urdu-Translation-Using-RNN-and-LSTM-Architectures

This repository contains the implementation of a Many-to-Many Recurrent Neural Network (RNN) and Long Short-Term Memory (LSTM) model for English-to-Urdu language translation. The project explores the limitations of RNNs in handling language translation and demonstrates how LSTM architectures overcome these challenges. The implementation utilizes a parallel corpus dataset for training and evaluation.

Achievements
Part 1: Many-to-Many RNN for English-to-Urdu Translation

Preprocessed the parallel-corpus.xlsx dataset containing English-Urdu sentence pairs.
Split the dataset into training, validation, and test sets.
Implemented a many-to-many RNN model using TensorFlow/PyTorch for English-to-Urdu translation.
Evaluated the RNN model using metrics like BLEU score and accuracy, and provided example translations from the test set.
Part 2: Limitations of RNNs

Discussed RNN challenges, including:
Handling long sequences due to exploding/vanishing gradients.
Difficulty capturing long-term dependencies, especially in Urdu's complex grammatical structures.
Poor performance on large datasets and complex language pairs.
Demonstrated examples where the RNN struggled with these limitations.
Part 3: Resolving RNN Limitations Using LSTM

Replaced RNN layers with LSTM layers to address its shortcomings.
Compared the performance of RNN and LSTM models using BLEU scores and accuracy.
Showed how LSTM's architecture resolves vanishing gradients and captures long-term dependencies effectively.
Highlighted remaining challenges in English-to-Urdu translation even with LSTM and suggested further improvements (e.g., incorporating attention mechanisms).
Deliverables
Code Implementation: Python files with well-documented RNN and LSTM models.
Data Preprocessing: Cleaned and split dataset for training and evaluation.
Evaluation Metrics: BLEU scores and accuracy comparisons for RNN and LSTM models.
Examples: Sample translations from both RNN and LSTM models.
Final Report: Detailed discussion of RNN and LSTM performance, limitations, and future improvement suggestions.
Tools and Libraries
Deep Learning Framework: TensorFlow or PyTorch
Data Handling: pandas, NumPy
Evaluation: BLEU score calculation libraries
Dataset: parallel-corpus.xlsx (English-Urdu sentence pairs)
This repository serves as a comprehensive implementation and analysis of RNN and LSTM architectures for language translation, focusing on the unique challenges posed by English-Urdu translation tasks.
