# 📝 Sentence Reordering with Transformers

![Python](https://img.shields.io/badge/Python-3.x-blue) ![TensorFlow](https://img.shields.io/badge/TensorFlow-2.x-orange) ![Keras](https://img.shields.io/badge/Keras-2.x-red) ![License](https://img.shields.io/badge/License-MIT-yellow)

This repository implements a **sentence reordering model** using the Transformer architecture, inspired by the "Attention Is All You Need" paper. The model aims to reorder shuffled sentences into coherent paragraphs for tasks like summarization and generation.

## 🔍 Introduction
The goal is to reorder shuffled sentences into a coherent sequence using the **Transformer model**, useful for tasks like text summarization and story generation.

## 📦 Requirements
- Python 3.7+
- TensorFlow
- Keras
- NumPy
- Pandas
- Matplotlib
- Scikit-learn

Install dependencies:
```bash
pip install tensorflow keras numpy pandas matplotlib scikit-learn

## 🔧 Notebook Structure
1. **Introduction**: Project overview.
2. **Data Preprocessing**: Tokenization and padding.
3. **Model Development**: Transformer model implementation.
4. **Training & Evaluation**: Training and validation.
5. **Experiments**: Exploring different architectures and hyperparameters.
6. **Conclusion**: Summary of results.

## ⚙️ Custom Callback
A custom callback monitors validation performance during training, enabling early stopping to prevent overfitting.

## 📉 Cosine Decay Restart
The learning rate follows a **Cosine Decay with Restarts** schedule to improve convergence by periodically reducing the learning rate.

## 📊 Results
The model achieved an average score of 0.573 on the test set, as monitored by the custom validation callback.

## 📝 Conclusion
The Transformer model showed average performance for sentence reordering, with minor improvements seen through different architectures and parameter tuning.

## 📚 References
- [A Comprehensive Study on Sentence Reordering](https://aclanthology.org/2021.naacl-main.134.pdf)
- [Attention Is All You Need](https://arxiv.org/pdf/1706.03762.pdf)
