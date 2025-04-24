# ml-security-classifier
### Introduction
In 2017, Microsoft released a groundbreaking dataset containing entries of real-world cybersecurity incidents. The dataset involved over 1 million annotated incidents with over 40 features and triage labels to denote the incident severity. The purpose of this project is to analyze this data and create an effective model for classifying how severe a particular security incident is based on the provided features. Each incident is given one of the following triage labels:

- TruePositive: Given to reported incidents corresponding to an actual attack or threat
- FalsePositive: Given to reported incidents that do not correspond to an actual attack or threat; a false report
- BenignPositive: Given to incidents correctly reported but determined to be harmless; an informational incident

Being able to precisely classify incidents into these labels is critical to addressing security incidents in a timely manner, especially at this scale. Security experts will be better equipped to prioritize certain reported incidents over others if provided with an effective classification model. This project aims to create such a model.

### Results

| Model        | Accuracy (%) |
|--------------|------------- |
| Logistic Regression| 61.9   |
| Random Forest      | 81.2   |
| XGB Classifier     |**92.2**|
| LGBM Classifier    | 90.7   |