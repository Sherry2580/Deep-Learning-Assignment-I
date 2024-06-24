# Image Classification with Multiple Models and Features

## Goal 
Implement an image classification system using at least three different classification models and three different image feature extraction methods. The goal is to analyze how different features and models affect the performance of image classification. To address this issue, it is necessary to explore methods for normalizing feature dimensions, such as feature encoding or pooling strategies, and consider how to adapt the bag-of-words model to handle feature vectors of varying lengths.

## Model Comparison

- Method 1 : Color Histogram

| Model         | Accuracy | F1 Score | Time  |
| ------------- | -------- | -------- | -------- |
| SVM           | 0.06     | 0.0281     | 36min 57s  |
| KNN           | 0.045    | 0.0364    | 19min 21s     |
| Random Forest | 0.115    | 0.0752     | 19min 21s  |

- Method 2 : HOG

| Model         | Accuracy | F1 Score | Time (s) |
| ------------- | -------- | -------- | -------- |
| SVM           | 0.05     | 0.0294     | 1h 47min 10s  |
| KNN           | 0.02     | 0.0083     | 2.27 s     |
| Random Forest | 0.055    | 0.0337     | 30min 26s   |

- Method 3 : SIFT

| Model         | Accuracy | F1 Score | Time (s) |
| ------------- | -------- | -------- | -------- |
| SVM           | 0.11     | 0.0802     | 37min 46s  |
| KNN           | 0.02     | 0.0175     | 580 ms   |
| Random Forest | 0.045    | 0.0293     | 13min 19s   |
