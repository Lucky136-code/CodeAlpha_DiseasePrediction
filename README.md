# CodeAlpha_DiseasePrediction
# Heart Disease Prediction using Machine Learning

This project focuses on predicting the likelihood of heart disease using the Cleveland Heart Disease dataset from the UCI Machine Learning Repository
. The dataset contains medical attributes such as age, sex, cholesterol levels, resting blood pressure, fasting blood sugar, and more, with the target variable indicating the presence of heart disease.

Workflow

  1.Data Loading & Preprocessing-
     The dataset is loaded into a pandas DataFrame with appropriate column names.
     Missing values in the ca and thal columns are imputed using the most frequent values.
     Categorical variables (sex, cp, fbs, restecg, exang, slope, ca, thal) are encoded using One-Hot Encoding to convert them into machine-readable form.

  2.Feature Engineering & Splitting-
     Features (X) and the target variable (y) are separated.
     Data is split into training (80%) and testing (20%) sets.

  3.Model Training-
    Four models are implemented:
       .Support Vector Machine (SVM)
       .Logistic Regression
       .Random Forest Classifier
       .XGBoost Classifier

  4.Evaluation-
     Models are evaluated using Accuracy, Precision, Recall, and F1-score.
     The model with the highest F1-score is selected as the best performer.

Results-
The evaluation identifies the most reliable model for heart disease prediction, ensuring balance between precision and recall. The best-performing model is used to generate predictions on test data.
This project demonstrates the complete pipeline for a supervised classification task, from raw dataset handling to model evaluation and selection.
