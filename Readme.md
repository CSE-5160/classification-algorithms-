# Project Title

A brief description of your project and its purpose.

## Table of Contents

- [Introduction](#introduction)
- [Installation](#installation)
- [Usage](#usage)
  - [Dataset](#dataset)
  - [Model Training](#model-training)
  - [Evaluating Performance with Classification Report](#evaluating-performance-with-classification-report)
- [Contributing](#contributing)
- [License](#license)

## Introduction

This project implements a machine learning model to predict labels based on textual data, utilizing various preprocessing techniques and evaluation metrics, including the classification report.

## Installation

To set up the project, ensure you have Python 3.6 or later installed. You can install the necessary libraries using pip:

```bash
pip install pandas scikit-learn numpy


# Model Performance Summary

This document provides a summary of the performance metrics for different machine learning models evaluated on both the training and test sets.

| Model             | Metric                  | Train Set Performance             | Test Set Performance              |
|-------------------|-------------------------|-----------------------------------|-----------------------------------|
| Linear Regression  | Mean Squared Error      | 1.1717596725456537e-06           | 0.028087724333759903              |
|                   | R² Score                | 0.9999952473974717                | 0.8863064599446707                |
| Naive Bayes       | Precision (0)           | 0.98                              | 0.98                              |
|                   | Recall (0)              | 1.00                              | 1.00                              |
|                   | F1-score (0)            | 0.99                              | 0.99                              |
|                   | Support (0)             | 13822                             | 3490                              |
|                   | Precision (1)           | 1.00                              | 1.00                              |
|                   | Recall (1)              | 0.99                              | 0.98                              |
|                   | F1-score (1)            | 0.99                              | 0.99                              |
|                   | Support (1)             | 17501                             | 4341                              |
|                   | Accuracy                | 0.99                              | 0.99                              |
| Random Forest      | Precision (0)           | 1.00                              | 0.99                              |
|                   | Recall (0)              | 1.00                              | 0.99                              |
|                   | F1-score (0)            | 1.00                              | 0.99                              |
|                   | Support (0)             | 13822                             | 3490                              |
|                   | Precision (1)           | 1.00                              | 0.99                              |
|                   | Recall (1)              | 1.00                              | 0.99                              |
|                   | F1-score (1)            | 1.00                              | 0.99                              |
|                   | Support (1)             | 17501                             | 4341                              |
|                   | Accuracy                | 1.00                              | 0.99                              |
