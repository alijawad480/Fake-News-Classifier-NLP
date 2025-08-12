
# 📰 Fake News Classifier (LSTM + Regularization)

A deep learning project to classify news articles as **Real** or **Fake** using **LSTM networks**.  
The model is trained with **Mini-batch Gradient Descent**, **L2 Regularization**, and **Dropout** to prevent overfitting, using a cleaned text **corpus** for better generalization.

---

## 📌 Features
- **Text Preprocessing & Corpus Creation**
- **Tokenization & Padding**
- **LSTM Neural Network**
- **Dropout Layers for Regularization**
- **L2 Regularization (Kernel Regularizer)**
- **Mini-batch Gradient Descent**
- **Model Evaluation & Accuracy/Loss Visualization**

---

## 📂 Dataset
We use a dataset containing news headlines and their labels:
- **Fake News** → Label `0`
- **Real News** → Label `1`
---

Preprocess Text & Build Corpus
Lowercasing

Removing punctuation & stopwords

Tokenization using Keras Tokenizer

Creating a corpus (list of cleaned sentences)

Padding sequences to the same length

Regularization Techniques Used
L2 Regularization: Prevents large weight values by adding a penalty term.

Dropout: Randomly drops neurons during training to avoid overfitting.

Mini-batch Gradient Descent: Improves convergence and stability.
