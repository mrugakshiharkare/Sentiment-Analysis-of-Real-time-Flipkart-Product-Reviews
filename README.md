# Real-Time Flipkart Product Review Sentiment Analysis

This project focuses on analyzing customer sentiment from real-time product reviews on Flipkart. Using Natural Language Processing (NLP) and Machine Learning, the system classifies reviews into positive, negative, or neutral categories to help businesses understand customer satisfaction and product performance.

## 📊 Project Overview

Customer feedback is a goldmine for e-commerce growth. This project implements an end-to-end data science pipeline to:
1. **Scrape/Collect** real-time product reviews.
2. **Preprocess** text data (Cleaning, Tokenization, Lemmatization).
3. **Analyze Sentiment** using Machine Learning models to quantify customer emotions.

## 🛠️ Tech Stack

* **Language:** Python 3.x
* **Libraries:** * `Pandas` & `NumPy` (Data Manipulation)
    * `NLTK` / `TextBlob` / `VADER` (Natural Language Processing)
    * `Scikit-learn` (Machine Learning Models)
    * `Matplotlib` & `Seaborn` (Data Visualization)
* **Environment:** Jupyter Notebook / VS Code

## 🧠 Key Features

* **Text Preprocessing:** Automated cleaning of reviews (removing stopwords, punctuation, and special characters).
* **Feature Engineering:** Implementation of TF-IDF or Bag-of-Words for numerical text representation.
* **Sentiment Classification:** Models used to predict review polarity.
* **Data Visualization:** Word clouds for positive/negative words and distribution plots for ratings.

## 📂 Project Structure

* `data/`: Contains the dataset (e.g., `flipkart_reviews.csv`).
* `notebooks/`: Jupyter notebooks covering EDA and Model Building.
* `src/`: Python scripts for data cleaning and sentiment scoring.
* `requirements.txt`: List of dependencies to run the project.

## 🚀 How to Run

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/mrugakshiharkare/Sentiment-Analysis-of-Real-time-Flipkart-Product-Reviews.git](https://github.com/mrugakshiharkare/Sentiment-Analysis-of-Real-time-Flipkart-Product-Reviews.git)
    cd Sentiment-Analysis-of-Real-time-Flipkart-Product-Reviews
    ```

2.  **Install dependencies:**
    ```bash
    pip install -r requirements.txt
    ```

3.  **Run the analysis:**
    Execute the Jupyter notebook or run the main python script to see the sentiment results.

## 📈 Results

* Successfully categorized reviews with an accuracy of [Insert your Accuracy % here].
* Identified key product pain points through negative review word clouds.

---
Developed as part of my Data Science and AI/ML practice.
