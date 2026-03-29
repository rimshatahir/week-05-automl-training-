# Confusion Matrix and Evaluation Metrics

## Confusion Matrix

|                | Predicted Phishing | Predicted Legitimate |
|----------------|-------------------|----------------------|
| Actual Phishing | 3 (True Positive) | 0 (False Negative)   |
| Actual Legitimate | 2 (False Positive) | 0 (True Negative) |

## Explanation

The confusion matrix shows how well the model performed when classifying phishing and legitimate inputs.

- True Positives (TP): The model correctly identified phishing inputs.
- False Positives (FP): Legitimate inputs were incorrectly labeled as phishing.
- False Negatives (FN): Phishing inputs that the model failed to detect.
- True Negatives (TN): Legitimate inputs correctly identified.

In this case, the model shows **high recall** because it successfully identified most phishing attempts. However, it has **low precision** because it incorrectly labels legitimate inputs as phishing.

## Metrics

- **Accuracy:** Moderate, due to incorrect classification of legitimate inputs
- **Precision:** Low, because of high false positives
- **Recall:** High, since phishing inputs were detected successfully

## Conclusion

The model is biased toward predicting phishing. While it is effective at catching threats, it needs improvement in distinguishing between legitimate and malicious inputs. This can be improved by using more balanced and diverse training data.
