# Titanic Survival Prediction – CodSoft

## Objective
Build a classification model to predict whether a passenger survived the Titanic disaster based on their features such as age, sex, class, and fare.

## Dataset
- **Source:** Titanic dataset (available in seaborn or Kaggle)
- **Features used:**
  - pclass (Passenger class)
  - sex (Gender)
  - age
  - sibsp (Number of siblings/spouses aboard)
  - parch (Number of parents/children aboard)
  - fare
  - embarked (Port of Embarkation)

## Technologies Used
- Python
- pandas
- scikit-learn
- seaborn

## Steps Performed
1. Imported required libraries.
2. Loaded the Titanic dataset.
3. Explored dataset structure and checked for missing values.
4. Handled missing values:
   - Filled missing age values with median age.
   - Dropped rows with missing embarked values.
5. Converted categorical variables using one-hot encoding (sex and embarked).
6. Selected relevant features for model training.
7. Split dataset into training and testing sets.
8. Trained a Decision Tree Classifier model.
9. Made survival predictions on the test data.
10. Evaluated model performance using:
    - Accuracy Score
    - Classification Report
11. Predicted survival for a sample passenger input with specific features.

## Results
- **Accuracy Score:** [Your Output]
- The model successfully predicts passenger survival status with reasonable accuracy given feature limitations.

## Sample Prediction
- **Input:** Pclass=3, Age=22, SibSp=1, Parch=0, Fare=7.25, sex_male=1, embarked_Q=0, embarked_S=1
- **Output:** Predicted survival (1 = Survived, 0 = Did not survive)

## Files
- titanic_survival_prediction.ipynb: Jupyter notebook containing complete code, outputs, and sample predictions.

## How to Run
1. Clone the repository or download files.
2. Install required packages:
    ```
    pip install pandas scikit-learn seaborn
    ```
3. Open `titanic_survival_prediction.ipynb` in Jupyter or Google Colab.
4. Run all cells to view outputs and sample predictions.

## Task Details
- **Internship:** CodSoft Data Science Internship
- **Task:** Titanic Survival Prediction
- **Submitted by:** [Your Name]

## Contact
For queries, connect via [LinkedIn/GitHub profile link].

## Conclusion
This project demonstrates classification using decision trees and preprocessing techniques to handle missing and categorical data effectively for predicting Titanic passenger survival.
