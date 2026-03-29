# Week 05 - AutoML Training Project

## Overview
This project focuses on building and evaluating a machine learning model using Teachable Machine to classify images as phishing or legitimate. The goal is to explore how AutoML can be applied to real-world cybersecurity problems, specifically phishing detection.

## Dataset
The dataset consists of:
- Phishing images (fake or malicious messages)
- Legitimate images (normal and safe messages)

Each class contains 21 images used for training and testing.

## Tools Used
- Teachable Machine (Google)
- GitHub
- CSV for result comparison

## Model Training
The model was trained using two classes:
- Phishing
- Legitimate

After uploading images for both categories, the model was trained directly in Teachable Machine.

## Testing
The model was tested using new images to evaluate performance:
- One example showed a correct classification
- Another example showed an incorrect classification

Screenshots are included in the repository.

## Results
The results are stored in: results/comparison-table.csv


This file compares predictions from:
- Generic model
- Fine-tuned models

## Evaluation
The confusion matrix and evaluation metrics are included in: metrics/confusion-matrix.md

## Key Findings
- The model achieved high recall for phishing detection
- It struggled with precision due to false positives
- The model is slightly biased toward predicting phishing

## Conclusion
This project demonstrates how AutoML tools like Teachable Machine can be used to detect phishing attempts. However, model performance depends heavily on the quality and diversity of training data.

