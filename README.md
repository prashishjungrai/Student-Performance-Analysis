This project applies supervised machine learning to analyze and predict student academic outcomes. Using regression techniques, the goal is to both estimate student scores in specific subjects and classify students as pass/fail, providing insights into academic performance and influencing factors.

Key Features:

Data Preprocessing:
Cleaned and structured the dataset.Encoded categorical variables such as gender, part-time job, and extracurricular activities.Scaled numerical features for better model performance.

Linear Regression (Score Prediction):
Built models to predict subject scores (e.g., Math) using features like study hours, absences, and activities.Evaluated performance using R² score.

Logistic Regression (Pass/Fail Classification):
Classified students into pass/fail categories based on average scores.Evaluated performance using accuracy, precision, recall, F1-score, and confusion matrix.

Result Analysis:
Found that study hours and absences strongly influence academic performance.Logistic regression achieved high accuracy, but results highlighted class imbalance (most students passed).

Technologies:
Python,Pandas, NumPy,Matplotlib, Seaborn,Scikit-learn 
