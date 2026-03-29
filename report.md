# Week 05 AutoML Training Report

## Introduction
In this project, a machine learning model was developed using Teachable Machine to classify images as phishing or legitimate. The goal was to explore how AutoML tools can be applied to cybersecurity problems, specifically phishing detection.

## Methodology
Two classes were created:
- Phishing
- Legitimate

Each class contained 21 images. These images were uploaded into Teachable Machine and used to train the model. The model was trained using default settings.

After training, the model was tested using new images to evaluate its performance.

## Results
The model produced mixed results:

- In one case, the model correctly identified a phishing image with high confidence (100% phishing).
- In another case, the model incorrectly classified an image, showing confusion between phishing and legitimate categories.

These results are supported by screenshots included in the repository.

Additionally, model outputs were compared using different approaches, and the results were recorded in the comparison table.

## Analysis
The confusion matrix shows that:
- The model has high recall, meaning it can detect phishing attempts effectively.
- However, it has low precision due to false positives, where legitimate inputs are flagged as phishing.

This indicates that the model is biased toward predicting phishing.

## Challenges
- Limited dataset size
- Lack of diversity in legitimate examples
- Visual similarities between phishing and legitimate messages

## Improvements
To improve the model:
- Increase the number of training images
- Add more diverse legitimate examples
- Balance the dataset more effectively
- Fine-tune model parameters

## Conclusion
The project demonstrates that AutoML tools can be used to build phishing detection models quickly. However, the effectiveness of the model depends on the quality of training data. While the model performs well in detecting phishing, improvements are needed to reduce false positives and increase overall accuracy.
