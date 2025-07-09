# diabetes-prediction-ml-svc-nb-dt
# Diabetes Prediction using Machine Learning and Flask

This is a web-based application that predicts whether a person is diabetic or not based on health parameters using a trained ML model (SVC, Decision Tree, or Naive Bayes).

## 🧠 Machine Learning Models Used
- Decision Tree
- SVC (Support Vector Classifier)
- Naive Bayes
- Feature Scaling using StandardScaler

  ## 🛠️ Tech Stack
- Python
- Flask (Web Framework)
- HTML (Frontend)
- scikit-learn
- pandas, numpy, seaborn, matplotlib

  ## 📁 Project Structure
  ├── Model/
│ ├── standardScaler.pkl
│ └── modelForPrediction.pkl
├── templates/
│ ├── index.html
│ └── single_prediction.html
├── diabetes.csv
├── app.py
├── requirements.txt
└── README.md
## 🧪 Features
- User inputs 8 health metrics
- Model predicts if the person is **Diabetic** or **Non-Diabetic**
- Clean UI using Flask templates

  
## 📈 Conclusion

This project compared three supervised machine learning models to predict diabetes:

| Model              | Accuracy |
|-------------------|----------|
| Decision Tree      | 68%      |
| Naive Bayes        | 72%      |
| Support Vector Classifier (SVC) | **73%** |

- 🔍 **SVC performed the best** among the three models with **73% accuracy**, making it the default choice in the deployed Flask app.
- 📉 The Decision Tree had the lowest performance, which might be due to its simplicity and tendency to overfit.
- 📊 Naive Bayes showed decent results and can be a fast alternative in low-resource environments.
