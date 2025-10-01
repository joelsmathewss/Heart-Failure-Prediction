# 🫀 Heart Disease Prediction using Machine Learning.

This project applies **machine learning techniques** to predict the presence of heart disease based on patient health records.  
By leveraging models like Logistic Regression, Support Vector Machines, Decision Trees, K-Nearest Neighbors, and Random Forests, we aim to build a reliable system that can assist in early diagnosis.

---


## 🚀 Methodology
1. **Data Preprocessing**
   - Handled missing values  
   - Encoded categorical features  
   - Normalized numerical features  

2. **Exploratory Data Analysis**
   - Correlation heatmaps  
   - Distribution plots  
   - Feature importance visualization  

3. **Model Training**
   - Trained 5 classifiers:
     - Logistic Regression  
     - Support Vector Machine (SVM)  
     - Decision Tree  
     - K-Nearest Neighbors (KNN)  
     - Random Forest  

4. **Evaluation Metrics**
   - Accuracy  
   - Cross-validation Score  
   - ROC–AUC  

---

## 📈 Results
| Model                  | Accuracy | Cross-Validation | ROC-AUC |
|-------------------------|----------|------------------|---------|
| Logistic Regression     | 87.5%    | 88.57%           | 87.4%   |
| SVM                     | 87.5%    | 90.25%           | 87.4%   |
| Decision Tree           | 79.16%   | 82.73%           | 78.7%   |
| KNN                     | 75%      | 82.13%           | 76.7%   |
| Random Forest           | 83.33%   | **92.91%**       | 83.2%   |

**Best Model:**  
- **Logistic Regression & SVM** → Best accuracy (87.5%)  
- **Random Forest** → Best generalization (92.91% CV score)  

---

## 📝 Conclusions
- Machine learning can accurately predict heart disease with **~85–90% accuracy**.  
- **Logistic Regression & SVM** are strong interpretable models.  
- **Random Forest** generalizes best and is recommended for deployment.  
- Key risk factors: **Chest Pain Type, ST Slope, Max Heart Rate, Oldpeak, Sex**.  
