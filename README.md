[![License](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
\[![Python Version](https://img.shields.io/badge/Python-3.x-green.svg)]
\[![Status](https://img.shields.io/badge/Status-Complete-brightgreen.svg)]

# RestoMood 🍽️🔍

## 🚀 Project Overview

RestoMood is a sentiment analysis pipeline designed to classify restaurant reviews as **positive** or **negative**. Leveraging NLP techniques and machine learning, this project transforms raw text feedback into actionable insights, enabling businesses to gauge customer satisfaction effectively.

## 🎯 Key Objectives

* **Text Preprocessing:** Clean and normalize review data to eliminate noise.
* **Feature Engineering:** Convert text into numerical vectors using the Bag-of-Words approach.
* **Model Training:** Employ Naive Bayes classifier for robust sentiment prediction.
* **Performance Evaluation:** Measure and optimize model accuracy on unseen data.

## 🛠️ Features & Highlights

| Feature                  | Description                                                    |
| ------------------------ | -------------------------------------------------------------- |
| **Data Cleaning**        | Remove punctuation, stopwords, and perform tokenization.       |
| **Vectorization**        | Apply Bag-of-Words to translate text into feature vectors.     |
| **Model Implementation** | Train and validate a Naive Bayes classifier on review data.    |
| **Performance Metrics**  | Evaluate using accuracy, precision, recall, and F1-score.      |
| **Deployable Pipeline**  | Modular code structure for easy integration into applications. |

## 🧰 Tech Stack & Libraries

* **Language:** Python 3.x
* **NLP & ML:** Scikit-learn
* **Data Handling:** Pandas, NumPy
* **Text Processing:** NLTK (stopwords, tokenization)
* **Notebook:** Jupyter Lab/Notebook

## 🚀 Getting Started

1. **Clone the repository**

   ```bash
   git clone https://github.com/yourusername/RestoMood.git
   cd RestoMood
   ```
2. **Run the Jupyter Notebook**

   * Launch Jupyter:

     ```bash
     jupyter lab   # or jupyter notebook
     ```
   * Open `Restaurant_Review_NLP.ipynb` and execute all cells.

> **Note:** No special environment setup is needed; commonly available Python libraries suffice.

## 📊 Results & Insights

* **Test Accuracy:** Achieved **73%** accuracy on the holdout set.
* **Model Strength:** Fast training and inference, suitable for real-time feedback.
* **Business Value:** Quickly pinpoint positive and negative trends in customer reviews.

## 🔗 Data Source

Customer review dataset compiled from public restaurant feedback repositories.

## 🤝 Contributors

* Sourish Chatterjee ([LinkedIn](https://www.linkedin.com/in/sourish-chatterjee/))

---

*Ready to mood-check restaurant reviews? Fire up the notebook and explore!*
