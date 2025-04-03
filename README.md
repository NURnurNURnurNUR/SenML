# SenML - Sentiment Analysis with Machine Learning  
A simple machine learning-based sentiment analysis tool using **Logistic Regression** and **TF-IDF Vectorization** with overall 86% accuracy result.

## Dataset link 
### "https://www.kaggle.com/datasets/snap/amazon-fine-food-reviews?resource=download"

## Features
- **Text Preprocessing**: Tokenization, Stopword Removal, Lemmatization
- **Sentiment Classification**: Predicts **Positive (2), Neutral (1), or Negative (0)**
- **Logistic Regression model** 
- **Gradio Interface**

## Installation & Setup
### 1. **Clone the repository**
```
git clone https://github.com/NURnurNURnurNUR/SenML.git
cd SenML
```
### 2. **Install Dependencies**
```
pandas
numpy
matplotlib
nltk
scikit-learn
```
## Training the Model
### 1. **Modify train_model.py to change dataset size or parameters**
### 2. **Train the model (if not already trained)**
### 3. **Save the Model and Vectorizer to use the Gradio Interface**
### 4. **Simply launch the Gradio Interface in "gradio_interface.ipynb"**

## Project Structure
SenML </br>
│── SenMl.ipynb   # Sentiment Analysis Model </br>
|── gradio_interface.ipynb # Web Interface </br>
│── Review.csv              # Dataset </br>
│── README.md                # Documentation </br>
│── .gitignore               # Files to ignore </br>
|── .gitattributes           # Prevent the Dataset from being diffed </br>


