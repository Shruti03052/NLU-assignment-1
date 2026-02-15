# Sport vs Politics Text Classification

## Project Overview

This project focuses on **binary text classification**, where a given text document is automatically classified as either **Sport** or **Politics**. The system uses classical machine learning techniques combined with different feature representation methods to analyze and compare model performance.

The project evaluates:
- Bag of Words (BoW)
- TF-IDF
- TF-IDF with N-grams

across three machine learning classifiers:
- Multinomial Naive Bayes
- Logistic Regression
- Support Vector Machine (Linear SVM)



## Dataset Description

### Source

The dataset is derived from the **20 Newsgroups dataset**, accessed using the `fetch_20newsgroups` utility from scikit-learn.

### Selected Categories

| Original Category | Mapped Label |
|------------------|-------------|
| rec.sport.baseball | Sport |
| rec.sport.hockey | Sport |
| talk.politics.guns | Politics |
| talk.politics.mideast | Politics |
| talk.politics.misc | Politics |

Documents from sports-related categories are labeled **Sport**, while political categories are labeled **Politics**.

##  Machine Learning Models

The following classifiers were implemented and compared:

- Multinomial Naive Bayes
- Logistic Regression
- Support Vector Machine (Linear SVM)
## Experimental Setup

- Feature representations evaluated independently
- Same train–test split used for all experiments
- Hyperparameters kept mostly default for fair comparison


