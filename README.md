# Diabetes Prediction with Machine Learning

This project aims to predict diabetes using the **Pima Indians Diabetes Dataset**.  
Two different data preprocessing strategies were applied, and various machine learning algorithms were evaluated.

## Dataset
- **Source:** Pima Indians Diabetes Dataset  
- **Features:** Age, BMI, Glucose level, etc.  
- **Target:** Predicting whether a person has diabetes (0 = No, 1 = Yes)

## Strategies
1. **Median Imputation:**  
   Zero values (considered as missing) were replaced with the median of each column.  
2. **Zero Removal:**  
   Rows containing zero values were completely removed from the dataset.

## Models Used
- Logistic Regression
- Support Vector Classifier (SVC)
- Decision Tree
- K-Nearest Neighbors (KNN)
- Random Forest
- AdaBoost

## Results

### Median Imputation Results
| Model                  | Accuracy |
|-------------------------|----------|
| Logistic Regression     | 0.75     |
| Support Vector Classifier | 0.75   |
| Decision Tree           | 0.72     |
| K-Nearest Neighbors     | 0.76     |
| Random Forest           | 0.75     |
| AdaBoost                | 0.77     |

### Zero Removal Results
| Model                  | Accuracy |
|-------------------------|----------|
| Logistic Regression     | 0.81     |
| Support Vector Classifier | 0.81   |
| Decision Tree           | 0.81     |
| K-Nearest Neighbors     | 0.76     |
| Random Forest           | 0.80     |
| AdaBoost                | 0.78     |

📌 **Overall Insight:**  
- The "Zero Removal" strategy generally achieved better performance.  
- Logistic Regression, SVC, and Decision Tree reached the highest accuracy (81%).  
