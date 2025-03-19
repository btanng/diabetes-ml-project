# Diabetes Prediction Using Machine Learning  

## Project Overview  
This project analyzes **diabetes risk factors** using machine learning techniques. The dataset consists of patient records from the CDC, including attributes like **BMI, income, education, and general health**. The goal is to identify key patterns and predict diabetes risk using various machine learning models.  

## Dataset  
- **Source**: CDC Patient Data  
- **Size**: 10,000+ patient records  
- **Features Analyzed**:  
  - Demographic factors (Income, Education)  
  - Health indicators (BMI, General Health, High Blood Pressure)  
  - Physical and mental well-being  

## Technologies Used  
- **Programming**: Python  
- **Libraries**: Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn  
- **Machine Learning Models**: Logistic Regression, K-Nearest Neighbors (KNN), Random Forest Classifier  

## Key Findings  
- **BMI and diabetes** show a strong correlation.  
- **Income and education levels** influence diabetes risk.  
- **Random Forest Classifier achieved the highest accuracy (85.26%)**, improving recall to **42.15%**.  

## Machine Learning Models Performance  
| Model                  | Accuracy | Recall  | F1-Score |
|------------------------|----------|---------|----------|
| **Logistic Regression** | 84.75%  | 38.64%  | 39.65%   |
| **K-Nearest Neighbors** | 81.22%  | 39.54%  | 40.22%   |
| **Random Forest**       | 85.26%  | 42.15%  | 43.78%   |
