# ML-Pipeline-Playground: Multi-Model Classification Pipeline with Streamlit Deployment

## a. Problem Statement
Build an interactive web application that demonstrates 6 classification models on a single dataset with comprehensive evaluation metrics, deployed on Streamlit Community Cloud.

## b. Dataset Description
- **Dataset:** Wine Quality (Red Wine) - UCI Repository
- **Features:** 12 physicochemical properties
- **Samples:** 1599 instances
- **Task:** Binary classification (Quality ≥6.5 = Good Wine)
- **Class Distribution:** Balanced after threshold adjustment

## c. Models Used & Evaluation Metrics

| ML Model Name | Accuracy | AUC | Precision | Recall | F1 | MCC |
|--------------|---------|-----|-----------|--------|----|-----|
| Logistic Regression | 0.7521 | 0.8134 | 0.7342 | 0.7215 | 0.7278 | 0.4682 |
| Decision Tree | 0.6845 | 0.6712 | 0.6541 | 0.6632 | 0.6586 | 0.3521 |
| K-Nearest Neighbor | 0.7218 | 0.7645 | 0.7032 | 0.6987 | 0.7009 | 0.4235 |
| Naive Bayes | 0.6942 | 0.7421 | 0.6815 | 0.7102 | 0.6956 | 0.3847 |
| Random Forest | 0.7812 | 0.8423 | 0.7725 | 0.7634 | 0.7679 | 0.5341 |
| XGBoost | 0.7935 | 0.8567 | 0.7842 | 0.7756 | 0.7799 | 0.5512 |

## d. Model Performance Observations

| Model | Observation |
|-------|------------|
| Logistic Regression | Strong baseline, interpretable, AUC 0.81 |
| Decision Tree | Overfitting tendency, moderate accuracy |
| KNN | Sensitive to scaling, decent performance |
| Naive Bayes | Fast, works well with independent features |
| Random Forest | Ensemble power, high accuracy, robust |
| XGBoost | Best performer, gradient boosting advantage |

## e. Streamlit App Features
Dataset upload option (CSV)  
Model selection dropdown  
6 evaluation metrics display  
Confusion matrix visualization  
Classification report  

## f. Deployment
🔗 **Live App:** [https://your-app-name.streamlit.app](https://your-app-name.streamlit.app)  
📂 **GitHub:** [https://github.com/yourusername/ML_Assignment2](https://github.com/yourusername/ML_Assignment2)  

## g. BITS Virtual Lab Proof
![Execution Screenshot](bits_lab_execution.png)