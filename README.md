# Movie Rating Prediction – CodSoft

## Objective
Build a regression model to predict movie ratings based on features such as budget, runtime, and number of votes.

## Dataset
- **Features used:**
  - Budget
  - Runtime
  - Votes
- **Target variable:** Movie Rating

(Note: Replace with your actual dataset details if using a real dataset.)

## Technologies Used
- Python
- pandas
- scikit-learn

## Steps Performed
1. Imported required libraries.
2. Loaded or created the movie dataset.
3. Explored dataset structure and checked for missing values.
4. Selected relevant features (Budget, Runtime, Votes) as input and Rating as output.
5. Split data into training and testing sets using train-test split.
6. Trained a Linear Regression model on the training data.
7. Made predictions on the test data.
8. Evaluated model performance using:
   - R2 Score
   - Mean Squared Error
9. Predicted rating for a sample movie input with specific features.

## Results
- **R2 Score:** [Your Output]
- **Mean Squared Error:** [Your Output]
- The model successfully predicts approximate movie ratings based on input features.

## Sample Prediction
- **Input:** Budget=130, Runtime=140, Votes=2000
- **Output:** Predicted movie rating (in IMDb scale or dataset scale)

## Files
- movie_rating_prediction.ipynb: Jupyter notebook containing complete code, outputs, and sample predictions.

## How to Run
1. Clone the repository or download files.
2. Install required packages:
    ```
    pip install pandas scikit-learn
    ```
3. Open `movie_rating_prediction.ipynb` in Jupyter or Google Colab.
4. Run all cells to view outputs and sample predictions.

## Task Details
- **Internship:** CodSoft Data Science Internship
- **Task:** Movie Rating Prediction
- **Submitted by:** [Your Name]

## Contact
For queries, connect via [LinkedIn/GitHub profile link].

## Conclusion
This project demonstrates the use of Linear Regression to predict continuous numerical outcomes (movie ratings) based on multiple numerical input features, strengthening regression modelling and evaluation skills.
