Sleep, Stress & Academic Performance Analysis
📌 Problem Statement

Does sleep deprivation negatively impact academic performance more than stress, and can students compensate for poor sleep through other factors?

This project analyzes the relationship between sleep, stress, and academic performance using an ordinal regression model, suitable for ordered outcome variables.

📊 Dataset

The analysis uses a student-level dataset capturing sleep behavior, stress levels, and academic outcomes.

Features Used in the Model:

1)Sleep Duration – Average sleep hours
2)Stress Level – Reported stress measure

Target Variable:
-Academic Performance (ordinal outcome)

The ordinal nature of academic performance makes ordinal logistic regression an appropriate modeling choice.

🛠️ Methodology

1)Data Loading
  -Dataset uploaded and loaded using Google Colab
  -Data inspected using Pandas

2)Modeling
  -Implemented Ordinal Logistic Regression using
  statsmodels.miscmodels.ordinal_model.OrderedModel

  -Logit distribution used for modeling ordered outcomes

3)Evaluation

  -Predicted class probabilities for each observation
  -Converted probabilities to class predictions
  -Model performance evaluated using Mean Absolute Error (MAE)

📈 Results & Insights

-Sleep duration shows a positive association with academic performance
-Higher stress levels negatively affect outcomes
-The model confirms that sleep and stress are key determinants of academic performance even without additional features

Evaluation Metric:
-Mean Absolute Error (MAE) used to assess prediction accuracy for ordered outcomes

🧠 Conclusion

The ordinal regression analysis highlights the importance of sleep and stress in determining academic performance.
The results suggest that managing stress and maintaining adequate sleep are critical for improved academic outcomes.

💻 Tech Stack
-Python
-Pandas – Data loading and analysis
-Statsmodels – Ordinal regression modeling
-Scikit-learn – Model evaluation (MAE)

🚀 How to Run the Project

1)Open the notebook in Google Colab
2)Upload the dataset file when prompted
3)Run all cells to:
  -Load the data
  -Fit the ordinal regression model
  -View model summary and MAE
