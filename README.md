# Task-04-Prodigy-InfoTech

# Sentiment Analysis – Text Cleaning & Exploratory Data Analysis

**Short Description:**
A Python-based NLP project focused on cleaning, exploring, and preprocessing textual data to prepare it for sentiment analysis, using exploratory data analysis and natural language processing techniques.

---

## Project Overview

This project focuses on **text data preprocessing and exploratory data analysis (EDA)** for sentiment analysis. The notebook demonstrates how raw, unstructured text data can be transformed into a clean and structured format suitable for downstream machine learning or NLP modeling.

The analysis includes handling missing values, removing duplicates, cleaning text, analyzing sentiment distributions, and applying common NLP preprocessing techniques such as tokenization, stopword removal, stemming, and lemmatization.

This project builds a strong foundation for **sentiment classification tasks** and reflects real-world workflows used in **Data Analytics, NLP, and Product Analytics**.

---

## Objectives

* Clean and preprocess raw text data
* Perform exploratory data analysis on sentiment labels
* Analyze text length and word distribution
* Apply NLP preprocessing techniques
* Prepare data for sentiment modeling

---

## Features

* **Data Cleaning**

  * Handling missing values
  * Removing duplicates
  * Filtering empty or invalid text entries

* **Exploratory Data Analysis (EDA)**

  * Sentiment distribution analysis
  * Text length and word count analysis
  * Visual comparisons across sentiment classes

* **Text Preprocessing**

  * Lowercasing text
  * Removing punctuation and special characters
  * Tokenization
  * Stopword removal
  * Stemming
  * Lemmatization

* **NLP-Ready Dataset**

  * Clean and structured text suitable for ML models

---

## Technologies Used

* **Python 3.x**
* **Pandas** – Data manipulation and cleaning
* **NumPy** – Numerical operations
* **Matplotlib** – Data visualization
* **Seaborn** – Statistical visualizations
* **NLTK** – Natural Language Processing
* **Jupyter Notebook**

---

## Dataset

**Type:** Text-based sentiment dataset

### Key Columns:

* `comment` / `text` – User-generated text data
* `sentiment` – Sentiment label (Positive, Neutral, Negative)

---

## Project Workflow

### 1. Data Loading

* Loaded the sentiment dataset into a Pandas DataFrame
* Inspected structure and data types

### 2. Data Cleaning

* Removed missing and duplicate text entries
* Filtered empty comments

### 3. Exploratory Data Analysis

* Analyzed sentiment label distribution
* Compared text lengths across sentiment classes
* Identified patterns in user expression

### 4. Text Preprocessing

* Converted text to lowercase
* Removed punctuation and noise
* Tokenized text into words
* Removed stopwords
* Applied stemming and lemmatization

### 5. Final Dataset Preparation

* Generated clean, processed text ready for modeling

---

## Code Structure

```
Task_04.ipynb
├── Import Libraries
├── Load Dataset
├── Data Inspection
├── Data Cleaning
│   ├── Handle missing values
│   ├── Remove duplicates
│   └── Filter empty comments
├── Exploratory Data Analysis (EDA)
│   ├── Sentiment Distribution
│   ├── Text Length Analysis
│   └── Word Count Analysis
├── Text Preprocessing
│   ├── Tokenization
│   ├── Stopword Removal
│   ├── Stemming
│   └── Lemmatization
└── Final Clean Dataset
```

---

## Key Insights

* Sentiment classes are unevenly distributed
* Positive, neutral, and negative comments differ significantly in length
* Raw text contains noise that must be removed before modeling
* Proper preprocessing improves text quality and model readiness

---

## Conclusion

This project demonstrates a complete **text preprocessing and exploratory analysis pipeline** for sentiment analysis. By cleaning raw text data, analyzing sentiment patterns, and applying NLP techniques, the notebook prepares the dataset for accurate and reliable sentiment classification.

The skills showcased—**text cleaning, EDA, NLP preprocessing, and insight extraction**—are directly applicable to real-world use cases such as **customer feedback analysis, product reviews, and social media monitoring**, making this project highly relevant for **Data Analyst, NLP, and Product Analyst roles**.

---

## Contributing

Contributions are welcome. Feel free to fork the repository and submit pull requests for improvements.

---

## Contact

**Aditya Gaur**

* Email: [work.adityagaur@gmail.com](mailto:work.adityagaur@gmail.com)
* LinkedIn: [https://linkedin.com/in/adityamnnit03](https://linkedin.com/in/adityamnnit03)

---

## License

This project is licensed under the **MIT License**.

---

## Acknowledgments

* NLP techniques inspired by standard text preprocessing practices
* Created as part of hands-on data analysis and NLP learning
* Developed for internship and portfolio preparation

---
 
 **Star this repository if you found it useful!**

 
