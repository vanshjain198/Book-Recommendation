# 📚 Book Recommendation System using Collaborative Filtering

## 📌 Overview

This project is a **machine learning–based book recommendation system** that suggests relevant books to users based on their past ratings and interaction patterns. It uses **Collaborative Filtering**, a widely used technique in recommender systems, to generate **personalized recommendations** by identifying similarities between users or books.

The project demonstrates an **end-to-end ML workflow**, including data preprocessing, exploratory data analysis, model building, and deployment using a simple web interface.

---

## 🎯 Objectives

- Build a personalized book recommender system
- Learn and apply collaborative filtering techniques
- Understand similarity-based recommendation logic
- Deploy the trained model for real-time predictions

---

## 🧠 Approach Used

The system is built using **Collaborative Filtering**, which works on the assumption that:

> **Users who agreed in the past will agree in the future.**

### Techniques Applied

- User–Item interaction matrix
- Filtering active users and popular books
- Cosine similarity to measure similarity between items/users
- Recommendation based on nearest neighbors

---

## 📂 Dataset

The project uses publicly available book datasets containing:

- **Books**: ISBN, title, author, publisher
- **Users**: User IDs and demographics
- **Ratings**: Explicit user ratings for books

### Preprocessing Steps

- Removing sparse users and books
- Merging datasets
- Handling missing and noisy data

---

## 🧾 Steps Used

1. Collected and loaded book, user, and rating datasets  
2. Performed data inspection and initial cleaning  
3. Removed users with very few ratings to reduce sparsity  
4. Filtered popular books with sufficient number of ratings  
5. Merged datasets to create a unified dataframe  
6. Constructed the user–item interaction matrix  
7. Computed similarity scores using cosine similarity  
8. Identified nearest neighbors based on similarity  
9. Implemented recommendation logic to suggest top books  
10. Serialized the trained model using Pickle  
11. Integrated the model with a simple web application  

---

## 🛠️ Tools & Technologies

- **Programming Language**: Python  

### Libraries

- Pandas  
- NumPy  
- Scikit-learn  

- **Model Handling**: Pickle  
- **IDE / Environment**: Jupyter Notebook, PyCharm  
- **Web Framework**: Streamlit / Flask  

---

## 🔄 Project Workflow

1. Data Loading and Inspection  
2. Data Cleaning and Preprocessing  
3. Exploratory Data Analysis (EDA)  
4. User–Item Matrix Construction  
5. Similarity Computation (Cosine Similarity)  
6. Recommendation Logic Implementation  
7. Model Serialization using Pickle  
8. Web App Integration  

---

## 🚀 Features

- Personalized book recommendations  
- Similarity-based suggestion engine  
- Lightweight and fast predictions  
- Simple and interactive UI  

---

## 📊 Results

- Successfully generates relevant book recommendations  
- Demonstrates effective use of collaborative filtering  
- Provides a scalable foundation for real-world recommender systems  

---

## 📌 Use Cases

- Online book stores  
- Content recommendation platforms  
- Learning recommender system fundamentals  
- ML portfolio project for freshers  

---



