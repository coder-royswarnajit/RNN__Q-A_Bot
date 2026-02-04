# Question Answering System with RNN and Optuna

This project implements a simple **Question Answering (QA) system** using a **Recurrent Neural Network (RNN)** in PyTorch. It leverages **Optuna** for hyperparameter optimization to automatically discover the best model configuration during training.

The system is trained on a small dataset of **100 unique question–answer pairs** and demonstrates how sequence models can be used for basic QA tasks.

---

## 🚀 Features

- **Data Loading**  
  Reads a CSV file containing question–answer pairs.

- **Text Preprocessing**  
  Includes tokenization, vocabulary construction, and text-to-index conversion.

- **Custom Dataset & DataLoader**  
  Implements a PyTorch-compatible `Dataset` and `DataLoader` for efficient batching.

- **RNN Model**  
  A basic RNN architecture for sequence modeling.

- **Hyperparameter Optimization with Optuna**  
  Tunes the following parameters automatically:
  - `embedding_size`
  - `hidden_size`
  - `learning_rate`
  - `epochs`

- **Prediction Function**  
  Provides a simple function to predict answers given a question.

---

## 📂 Dataset

The model is trained on a custom dataset of 100 unique QA pairs.

**Download dataset from:**  
https://drive.google.com/file/d/1X4Hcj72NK7J2JYvgjICFj0R1XwUq1w0a/view

Place the downloaded file as:

