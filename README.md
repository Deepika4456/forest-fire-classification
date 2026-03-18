 Brazil Forest Fire Classification

 Project Overview
This project focuses on classifying forest fire intensity in Brazil using Machine Learning techniques. The dataset contains information about fire occurrences across different states and months.

 Dataset
- Brazil Amazon Forest Fire Dataset
- Features:
  - Year
  - State
  - Month
  - Number of Fires
  - Date

 Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn

 Data Preprocessing
- Converted date column into datetime format
- Extracted day from date
- Handled missing values
- Encoded categorical variables (state, month)

 Problem Statement
Classify fire intensity into categories:
- 0 → No Fire
- 1 → Low
- 2 → Medium
- 3 → High

 Model Used
- Random Forest Classifier
- Decision Tree Classifier (for comparison)

 Model Evaluation
- Accuracy Score
- Confusion Matrix
- Classification Report

 Visualization
- Fire distribution across months
- State-wise fire analysis

 Output
- Fire classification predictions
- Saved model file (`fire_model.pkl`)
- Processed dataset

 How to Run
1. Open Anaconda Navigator
2. Launch Jupyter Notebook
3. Open `forest_fire.ipynb`
4. Run all cells

 Future Improvements
- Use advanced models like XGBoost
- Deploy as a web app
- Add real-time fire prediction

 Author
Deepika Surisetti
