# 🤖 AWS FAQ Chatbot

This project demonstrates how to build a simple FAQ-style chatbot for AWS-related questions using **TF-IDF vectorization** and **cosine similarity**. It retrieves the most relevant answer from a dataset of AWS FAQs based on user input.

---

## 📂 Project Structure

- `AWS_FAQ_Bot.csv` — Dataset containing AWS Questions and Answers  
- `AWS_FAQ_Chatbot_Cleaned.ipynb` — Cleaned and presentable Jupyter notebook with chatbot logic

---

## 🚀 Features

- Load and clean real AWS FAQ data  
- Transform questions using `TfidfVectorizer`  
- Match user queries using `cosine_similarity`  
- Loop-based command line chatbot interface  

---

## 📊 Tech Stack

- Python  
- Pandas  
- Scikit-learn  
- NumPy
- TF-IDF
- Cosine Similarity
- NLP

---


## 💡 How It Works

1. Loads the AWS FAQ dataset from CSV  
2. Cleans missing values  
3. Converts questions to TF-IDF vectors  
4. Compares user input against FAQ questions using cosine similarity  
5. Returns the best-matching answer


---

