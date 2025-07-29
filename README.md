Churn_Prediction_Comparison
This project aims to predict customer churn using supervised machine learning techniques. It compares the performance of two models: Logistic Regression and Random Forest Classifier, using evaluation metrics and data visualizations.

 Project Objective

- Predict whether a customer is likely to churn based on historical data.
- Implement and train two different ML models.
- Compare model performance using accuracy, precision, recall, F1-score, and AUC.
- Provide meaningful visualizations to support the comparison.

 Dataset

- Name: Telco Customer Churn Dataset  
- Source: https://www.kaggle.com/datasets/blastchar/telco-customer-churn  
- Records: 7043 customers  
- Features: Demographics, service usage, billing details, churn flag

 Technologies Used

- Python 3.x  
- Pandas, NumPy  
- Scikit-learn  
- Matplotlib, Seaborn  

 Project Structure

churn_project/  
├── Telco-Customer-Churn.csv        # Dataset file  
├── churn_analysis.py               # Main analysis script  
├── requirements.txt                # Required Python libraries  
└── README.md                       # Project documentation  

 Steps Performed

1. Data loading and preprocessing (handling missing values, encoding, scaling)  
2. Splitting data into training and test sets  
3. Training two models:  
   - Logistic Regression  
   - Random Forest Classifier  
4. Predicting on test data  
5. Evaluating using:
   - Accuracy  
   - Classification report (precision, recall, F1-score)  
   - Confusion matrix  
   - ROC Curve  
   - Accuracy comparison chart  

 Visual Outputs

- Confusion Matrices for both models  
- Bar chart comparing model accuracies  
- ROC Curve with AUC values  
- Heatmaps of classification metrics  

 How to Run

1. Clone the repository or download the files  
2. Install the required libraries:
