# IMDB Sentiment Classifier using BERT

A transformer-based Natural Language Processing (NLP) project that fine-tunes Google's **BERT (bert-base-uncased)** model on the IMDB Movie Reviews dataset to classify reviews as **Positive** or **Negative**. The project includes model training, evaluation, and an interactive **Gradio** web application for real-time sentiment prediction.

---

## Project Overview
Traditional machine learning models often rely on manually engineered features such as TF-IDF. In contrast, BERT generates contextual word representations, allowing it to understand the meaning of words based on surrounding context.

This project demonstrates the complete workflow of fine-tuning a pre-trained BERT model for binary sentiment classification using the Hugging Face ecosystem.

---

## Features
* Fine-tuned **BERT (bert-base-uncased)** model
* IMDB Movie Reviews Dataset
* Hugging Face Transformers & Datasets
* Interactive Gradio Web Interface
* Real-time Sentiment Prediction
* Model Evaluation using Accuracy, Precision, Recall and F1-score
* Clean and well-documented Jupyter Notebook

---

## Tech Stack
* Python
* PyTorch
* Hugging Face Transformers
* Hugging Face Datasets
* Gradio
* Scikit-learn
* NumPy
* Pandas
* Matplotlib

## Dataset
* Dataset: IMDB Movie Reviews
* Total Reviews: 50,000
* Training Samples: 25,000
* Testing Samples: 25,000
* Classes:
  * Positive
  * Negative

##Model
* Pre-trained Model: bert-base-uncased
* Task: Binary Sentiment Classification
* Framework: Hugging Face Transformers
* Optimizer: AdamW
* Loss Function: CrossEntropyLoss

---

## Evaluation Metrics
The model is evaluated using:

* Accuracy
* Precision
* Recall
* F1-score

---

##Gradio Application

The trained model is integrated with a Gradio interface that allows users to enter custom movie reviews and receive real-time sentiment predictions.

---

## 💡 Example

Input
```
The movie was absolutely amazing. The acting and story were fantastic.
```
Output
```
Positive 😊
```

---
## Possible Future Improvements
* Compare BERT with DistilBERT and RoBERTa
* Deploy on Hugging Face Spaces
* Support multilingual sentiment analysis
* Improve inference speed through model optimization

---

## Author
Developed as part of my Machine Learning and NLP portfolio using PyTorch, Hugging Face Transformers, and Gradio.

