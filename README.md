# Maths-Problem-Categorization
learning based methods to categorize mathematics question based on context of problem 

### Math Problem Categorization
## Overview

This project is part of a  maths community challenge aimed at developing a machine-learning model to accurately categorize math problems based on the text of the problem. The challenge provides an opportunity to apply and enhance text classification skills in the unique context of mathematical problems.

Mathematics encompasses various sub-domains, each with distinct problem types and solving methods. While educators can easily categorize problems into domains like algebra, calculus, or statistics, automating this process using machine learning is complex. This project aims to create a model that can assist educators by automatically categorizing math problems, making it easier to curate problems and focus on specific math domains.
Project Goal

The primary goal of this project is to build a machine learning model that:

  - Categorizes math problems into their respective domains based on the problem text.
  - Improves educational tools by automating the categorization of math problems.

Dataset

The dataset used in this project contains labeled math problems, categorized into various mathematical domains. The data is provided in CSV format, including features such as the problem text and its corresponding category.
Installation and Setup

To replicate this analysis, you'll need the following Python libraries:

  -  Pandas
  -  Numpy
  -  Scikit-learn
  -  Imbalanced-learn (SMOTE)
  -  Matplotlib
  -  TensorFlow (Keras)
  -  NLTK (for natural language processing)

Install the necessary packages via pip:
``` bash
 pip install pandas numpy scikit-learn imbalanced-learn matplotlib tensorflow nltk
```
Usage

  1. Data Preprocessing:
     -  Text preprocessing steps include tokenization, removing stopwords, and lemmatization using NLTK.
        Handling class imbalance using SMOTE (Synthetic Minority Over-sampling Technique).

  2. Feature Extraction:
     -  Extract features from the problem text using methods like TF-IDF (Term Frequency-Inverse Document Frequency).

  3. Model Training:
     - Build and train machine learning models such as Support Vector Machines (SVM) and LSTM-based neural networks.
       Evaluate model performance using metrics like accuracy.

  4. Prediction and Evaluation:
     - Use the trained model to categorize new math problems.
       Analyze the results and refine the model to improve accuracy.

Example Visualizations

  - Word Cloud: Visual representation of the most common terms in the dataset.
    Confusion Matrix: Evaluation of model performance in categorizing math problems.

Conclusion

This project demonstrates the application of text classification techniques to the educational domain, specifically in categorizing math problems. The developed model aims to assist educators by automating the classification process, making it easier to focus on specific areas of mathematics.

