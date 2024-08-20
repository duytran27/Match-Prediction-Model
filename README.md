# Football Match Prediction Model

This project focuses on developing a machine learning model to predict the outcomes of football matches. The model is built using historical match data and employs a Random Forest classifier to make predictions based on various features, including team performance metrics, match details, and referee assignments.

## Key Features

- **Data Preprocessing:**
  - Cleans and preprocesses the dataset, handling missing values.
  - Converts key information such as scores, dates, and match outcomes into formats usable by the model.

- **Feature Engineering:**
  - Computes rolling averages of goals and expected goals (xG) for each team over the last five matches.
  - Converts categorical features like match day, teams, referees, and venues into numerical formats using one-hot encoding.

- **Model Training:**
  - Trains a Random Forest classifier on historical data.
  - Uses GridSearchCV to perform hyperparameter tuning for optimal model performance.
  - Evaluates the model on a test set to ensure accuracy.

- **Match Prediction:**
  - Predicts the outcomes of hypothetical matches, such as a match between Manchester City and Liverpool, considering recent team performance and other factors.

## Technologies Used

- **Python**: For data processing, feature engineering, and model training.
- **Pandas**: For data manipulation and analysis.
- **Scikit-Learn**: For implementing and tuning the Random Forest model.
- **GridSearchCV**: For hyperparameter optimization.

## How to Use

1. Clone this repository to your local machine.
2. Ensure you have Python and the necessary packages installed (requirements.txt).
3. Load the provided Jupyter notebook and follow the steps to preprocess the data, train the model, and make predictions.

## Project Structure

- `Match Prediction Model.ipynb`: The main notebook containing all the steps from data preprocessing to model evaluation and prediction.

## Contributing

Feel free to fork this repository and submit pull requests. Contributions are welcome!

## License

This project is open-source and available under the MIT License.
