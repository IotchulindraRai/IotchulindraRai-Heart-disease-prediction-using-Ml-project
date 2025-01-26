# IotchulindraRai-Heart-disease-prediction-using-Ml-project

IotchulindraRai/Heart-disease-prediction-using-Ml-project with GUI 
training models and make prediction based on model of dataset it was done for learning

linked in : https://np.linkedin.com/in/chulindra-rai-a51308206

🎯 Building a Machine Learning Model to Predict Heart Disease

✅ Dataset: The heart.csv file contains features like age, cholesterol, resting blood pressure, and more to predict the presence of heart disease (output).

🚀 Steps Taken:

1️⃣ Data Cleaning: Removed duplicates and ensured no missing values.

2️⃣ Feature Engineering:

Separated categorical (e.g., chest pain type) and continuous (e.g., age) variables.

Applied one-hot encoding for categorical variables.

Scaled continuous features using StandardScaler.

3️⃣ Model Training: Trained 6 different algorithms:

Logistic Regression (57% Accuracy)

SVM (80%)

KNN (78%)

Decision Tree (78%)

Random Forest (Best! 88%)

Gradient Boosting (77%)

4️⃣ Model Comparison: Visualized results with a bar plot to identify the top performer: Random Forest.

5️⃣ Deployment:

Saved the model using joblib.

Faced feature mismatch issues during new data predictions (fix needed!).

💡 Key Takeaways:

Preprocessing and feature engineering play a huge role in model performance.

Random Forest is a robust algorithm for this problem.

Consistency in feature names is crucial for smooth deployment.


GUI with final output :
![Screenshot_20230210_031514](https://user-images.githubusercontent.com/87846923/218144611-c5f4735e-5473-478a-82b8-1d33dacb91f2.png)
