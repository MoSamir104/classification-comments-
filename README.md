# YouTube Comment Spam/Ham Classification

This project focuses on classifying YouTube comments as **spam** or **ham** (non-spam) using machine learning. The dataset consists of 1956  balanced samples, and the primary model used is **XGBoost** with a **Bag of Words (BoW)** representation.

---

## Table of Contents
1. [Project Overview](#project-overview)
2. [Dataset](#dataset)

---

## Project Overview
The goal of this project is to build a machine learning model that can accurately classify YouTube comments as spam or ham. The project involves:
- Data cleaning and preprocessing.
- Feature engineering using BoW
- Model training and evaluation using XGBoost.
- Hyperparameter tuning and performance analysis.

---

## Dataset
The dataset contains the following columns:
- **author**: Name of the comment author.
- **date**: Timestamp of the comment.
- **text**: The comment text.
- **label**: Binary label (1 for spam, 0 for ham).
- **video**: Identifier for the video the comment belongs to.

The dataset is balanced, with an equal number of spam and ham comments.

---
