# Wildfire Prediction Using MobileNetV3: A Deep Learning Approach for Early Detection from Satellite Imagery

## Research Objectives
    To implement and evaluate MobileNetV3 for wildfire prediction using satellite imagery.
    To assess model performance based on key metrics such as accuracy, precision, recall, and F1-score.
    To optimize the data pipeline for efficient preprocessing, training, and inference.
    To visualize and analyze the predictions using Tableau for better interpretability.
    Compare and Contrast the Results

## Approach and Methodology
To achieve these objectives, we implemented MobileNetV3, The dataset consists of satellite images labelled based on past wildfire occurrences. 

## The methodology includes:
    
1. Data Preprocessing: Image standardization, augmentation, and label encoding.

2. Model Training: Training MobileNetV3 with 80% training and 20% test split.

3. Performance Evaluation: Measuring accuracy, precision, recall, F1-score, and analyzing confusion matrices.

4. Integration with SQL databases for efficient storage and retrieval.

5. Visualization and Insights: Using Tableau for exploratory data analysis (EDA) and prediction mapping.


## Data Vizualizations

![image](https://github.com/user-attachments/assets/afe2feb6-27e6-4d3e-80fe-08ffbcea3e05)

![image](https://github.com/user-attachments/assets/75d66e2d-0a9d-4cc2-8def-ed6ae710cdae)


## Results

High Accuracy (93%): MobileNetV3 is performing well, with a strong overall classification ability.
Slight Recall Imbalance:
Class 0 (Recall: 0.89) suggests that some negative samples are misclassified as positives.
Class 1 (Recall: 0.96) indicates the model is better at capturing positives than negatives.
Good Precision for Class 0 (0.95): The model is very confident when predicting Class 0, meaning few false positives
The F1-score for both classes is high, which means the model has a good balance of precision and recall.

![image](https://github.com/user-attachments/assets/e2b97996-7507-4d22-a5a6-703d63dc3312)


The Confusion Matrix Confirmed the results with: 
Overall Accuracy is 93%
High Recall for Class 1 (0.96) → Very few false negatives, meaning most Class 1 instances are detected.
Balanced F1-Score (Class 0: 0.92, Class 1: 0.94) → Performance is solid across both classes.
False Positives (62) are higher than False Negatives (27), suggesting the model sometimes mistakenly predicts Class 1 instead of Class 0

![image](https://github.com/user-attachments/assets/546e7fbf-b773-47aa-8c4d-33cfd8334787)


 # APPENDIX
 

