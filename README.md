# Fake Review Detector

Fake Review Detector is a machine learning based web application that identifies whether a product review is **genuine or fake**. The system uses Natural Language Processing (NLP) techniques and a trained **K-Nearest Neighbors (KNN)** model to classify reviews based on their content.

The goal of this project is to help detect misleading or spam reviews that can influence customer decisions on online platforms.

---

## Project Overview

Online reviews play a major role in influencing customer purchases. However, many platforms suffer from **fake or spam reviews** written to artificially promote or damage products.

This project uses **Machine Learning and NLP techniques** to analyze review text and predict whether the review is genuine or fake.

---

## Features

• Detects fake or genuine product reviews  
• Uses **Natural Language Processing (NLP)** for text analysis  
• Machine learning classification using **KNN algorithm**  
• Simple **web interface using Flask**  
• Fast prediction using pre-trained models  
• User-friendly interface for entering review text  

---

## Technologies Used

### Programming Language
Python

### Machine Learning
- Scikit-learn
- K-Nearest Neighbors (KNN)

### Natural Language Processing
- TF-IDF Vectorization

### Web Framework
- Flask

### Frontend
- HTML
- CSS

### Model Storage
- Joblib

---

## Project Structure
fake-review-detector
│
├── static
│ └── (CSS files, images, background)
│
├── templates
│ └── HTML files for web interface
│
├── venv
│ └── virtual environment
│
├── app.py
│ └── Flask application for running the web app
│
├── knn_model.joblib
│ └── Trained KNN machine learning model
│
├── vectorizer.joblib
│ └── TF-IDF vectorizer used for text transformation
│
├── requirements.txt
│ └── Project dependencies
│
└── README.md

---

## How the System Works

1. The user enters a product review in the web interface.
2. The review text is processed using **TF-IDF vectorization**.
3. The transformed text is passed to the **trained KNN model**.
4. The model predicts whether the review is **fake or genuine**.
5. The result is displayed to the user on the webpage.

---

## Machine Learning Approach

• Text preprocessing  
• Feature extraction using **TF-IDF Vectorizer**  
• Classification using **K-Nearest Neighbors (KNN)**  
• Model saved using **Joblib** for fast deployment  

---

## Use Cases

• Detect fake product reviews on e-commerce platforms  
• Assist businesses in filtering spam reviews  
• Demonstrate practical applications of **NLP and Machine Learning**

---

## Future Improvements

• Use more advanced models like **Logistic Regression, SVM, or Deep Learning**  
• Improve dataset size for better accuracy  
• Add review sentiment analysis  
• Deploy the application online

---

## Author

Priyanka Gadekar,Dishti Andersahare,Shruti Mishra 
BTech Data Science Student  

Interested in **Machine Learning, Artificial Intelligence, and Data Science**
