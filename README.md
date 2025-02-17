# **N-gram Language Modeling & Movie Review Classification**  

## **Overview**  
This repo focuses on training a language model from scratch on **imdb movie review dataset** and utilizing it for two key NLP tasks:  

1. **Text Prediction** – Using **unigram, bigram, and trigram models** to predict the next word in a sequence.  
2. **Movie Review Classification** – Assigning labels to generated movie reviews based on learned patterns in the dataset.  

## **Features**  

### 📌 **Text Prediction**  
- **Unigram Model**: Predicts the most frequent word in the corpus.  
- **Bigram Model**: Predicts the next word based on the previous word.  
- **Trigram Model**: Predicts the next word based on the previous two words.  

### 🎬 **Movie Review Classification**  
- Implements **Bayesian classification** to label generated movie reviews.  
- Evaluates classification using standard metrics.  

## **Implementation Steps**  

### **1️⃣ Data Preparation**  
- Read and preprocess text corpus (convert to lowercase, remove punctuation).  

### **2️⃣ Model Building**  
- Construct **unigram, bigram, and trigram models** from the dataset.  

### **3️⃣ Prediction Function**  
- Predict the next word based on preceding words using the trained models.  

### **4️⃣ Review Classification**  
- Suggest labels for movie reviews using Bayesian classification.  

## **Technologies Used**  
- **Python** (without external ML libraries)  
- **Basic NLP techniques** (N-grams, Bayesian classification)  

🚀 **This project provides a deeper understanding of language modeling and text classification using fundamental NLP concepts!**
