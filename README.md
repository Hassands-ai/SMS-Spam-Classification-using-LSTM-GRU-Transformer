# SMS-Spam-Classification-using-LSTM-GRU-Transformer
Comparison of LSTM, GRU, and Transformer models for SMS Spam Classification using PyTorch with performance evaluation and comparative analysis.
# SMS Spam Classification using LSTM, GRU, and Transformer

This repository presents a comparative study of three deep learning architectures—LSTM, GRU, and Transformer—for SMS Spam Classification. The project was developed as part of the Generative AI Internship at the National Centre of Artificial Intelligence (NCAI), UET Lahore.

## Project Objective

The primary objective of this project is to classify SMS messages into two categories:

• Ham (Normal Message)
• Spam (Unwanted Message)

The project compares traditional sequential neural networks with modern attention-based architectures to understand their performance, computational efficiency, and generalization ability.

## Models Implemented

• Long Short-Term Memory (LSTM)
• Gated Recurrent Unit (GRU)
• Transformer Encoder

## Workflow

1. Data Loading
2. Text Preprocessing
3. Tokenization
4. Vocabulary Creation
5. Sequence Padding
6. Train/Validation/Test Split
7. Model Training
8. Performance Evaluation
9. Comparative Analysis

## Evaluation Metrics

• Accuracy
• Precision
• Recall
• F1-Score
• Confusion Matrix
• Classification Report

## Technologies Used

• Python
• PyTorch
• Pandas
• NumPy
• Scikit-learn
• Matplotlib
• NLTK

## Experimental Results

The performance of all three models was compared on the SMS Spam Collection dataset.

• LSTM achieved strong sequential learning performance.
• GRU provided faster training with fewer parameters than LSTM.
• Transformer achieved the highest classification accuracy by utilizing the self-attention mechanism to capture contextual relationships between words.

## Learning Outcomes

Through this project, I learned:

• Sequence modeling using Recurrent Neural Networks
• Difference between LSTM and GRU architectures
• Self-Attention mechanism
• Transformer Encoder architecture
• Performance comparison of deep learning models
• Hyperparameter tuning
• Model evaluation and analysis

This project serves as the foundation for the next stage of the internship, where pretrained Transformer models such as DistilBERT are fine-tuned using multiple transfer learning strategies.
