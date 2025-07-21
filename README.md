# Credit Card Fraud Detection – CodSoft

## Objective
Build a classification model to detect fraudulent credit card transactions using transaction features.

## Dataset
- **Source:** creditcard.csv (Kaggle)
- **Features:** Time, Amount, V1-V28 (anonymised principal components)
- **Target:** Class (0 = Not Fraud, 1 = Fraud)

## Technologies Used
- Python
- pandas
- scikit-learn

## Steps Performed
1. Imported required libraries.
2. Loaded the credit card dataset.
3. Explored dataset structure and checked class distribution (imbalanced).
4. Split data into features and target variable.
5. Performed train-test split (80-20).
6. Trained a Random Forest Classifier.
7. Made predictions on test data.
8. Evaluated model performance using:
   - Accuracy Score
   - Classification Report (Precision, Recall, F1-score)
   - Confusion Matrix
9. Predicted fraud status for a sample transaction input.

## Results
- **Accuracy:** [Your Output]
- The model effectively classifies transactions as fraudulent or not, though precision and recall are more important due to class imbalance.

## Sample Prediction
- **Input:** First row from test dataset
- **Output:** Predicted class (1 = Fraud, 0 = Not Fraud)

## Files
- credit_card_fraud_detection.ipynb: Jupyter notebook with complete code and outputs.

## How to Run
1. Clone this repository or download files.
2. Install required packages:
    ```
    pip install pandas scikit-learn
    ```
3. Ensure `creditcard.csv` is in your working directory.
4. Open `credit_card_fraud_detection.ipynb` in Jupyter or Google Colab.
5. Run all cells to view outputs and sample predictions.

## Task Details
- **Internship:** CodSoft Data Science Internship
- **Task:** Credit Card Fraud Detection
- **Submitted by:** [Your Name]

## Contact
For queries, connect via [LinkedIn/GitHub profile link].

## Conclusion
This project demonstrates binary classification on highly imbalanced datasets using ensemble methods for fraud detection applications.
