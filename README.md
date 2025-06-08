# Detecting-Fake-and-Real-News-with-NLP-and-ML

Fake and Real News Detection Using Machine Learning
## Overview
With the explosion of fake news across digital media platforms, distinguishing between credible and deceptive news has become critically important. This project aims to build a machine learning-based fake news detection system using NLP techniques and popular classification models like Logistic Regression, SVM, and Random Forest.

It includes a Tkinter-based GUI for easy user interaction, allowing users to enter custom text (news headlines or articles) and receive classification as Real or Fake.

## Features
Preprocessing with NLTK: Tokenization, stopword removal, stemming

Text vectorization using TF-IDF

Classification using:

Logistic Regression

Support Vector Machine

Random Forest

Model evaluation using Accuracy, Precision, Recall, and F1-Score

Interactive Tkinter GUI

Custom CSS styling for enhanced user interface visuals

Supports batch prediction

## Tools & Technologies
Tool	             Purpose
Python	           Core language
Jupyter notebook   environment
Scikit-learn	     ML modeling and evaluation
NLTK	             Text preprocessing (tokenization, stemming)
Tkinter	           GUI design
CSS	               Styling GUI

## screenshots

![image](https://github.com/user-attachments/assets/69abe06c-3b29-40bd-a1e5-662322a2ea54)
![image](https://github.com/user-attachments/assets/363e89e3-99a2-469a-a5b6-ec5bc62bd2dc)

## Results
Training Accuracy: ~98%

Testing Accuracy: ~93%

Metrics: Evaluated using Precision, Recall, and F1-Score

Best performance observed with Logistic Regression after TF-IDF transformation.


## Dataset
Contains labeled real and fake news articles.

Key fields: Title, Content, Subject, Publication Date, and Label.



