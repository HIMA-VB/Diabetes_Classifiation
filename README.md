# Diabetes_Classifiation

```markdown
# Decision Tree Classifier for Diabetes Prediction

This repository contains Python code for training a Decision Tree Classifier to predict diabetes based on various health attributes. The dataset used is the "diabetes.csv."

## Contents

1. **Data Loading and Preprocessing:**
    - The code loads the dataset from the `diabetes.csv` file.
    - Data preprocessing includes checking for missing values, describing the dataset, and examining the distribution of the target variable ("Outcome").

2. **Model Training:**
    - A Decision Tree Classifier is trained using the training data to predict diabetes based on health attributes.

3. **Model Evaluation:**
    - The code makes predictions on the test data using the trained model.
    - The accuracy score of the model is calculated using scikit-learn's `accuracy_score` function.

4. **Results:**
    - The results are printed to the console, including the accuracy score in percentage.

5. **Visualization:**
    - The Decision Tree Classifier can be visualized using graphical representations, such as a tree diagram.

6. **Dependencies:**
    - The code utilizes libraries such as pandas, numpy, matplotlib, and scikit-learn. Ensure you have these libraries installed.

## Usage

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/diabetes-prediction.git
   ```

2. Navigate to the project directory:
   ```bash
   cd diabetes-prediction
   ```

3. Run the Python script to train the Decision Tree Classifier and evaluate its performance:
   ```bash
   python decision_tree_diabetes.py
   ```

4. View the results in the script's output, including the accuracy score.

## Data

The dataset is loaded from the `diabetes.csv` file. Make sure you have the dataset available in the project directory or specify the correct file path in the code.

## License

This project is open-source and available under the [MIT License](LICENSE).

---

This code demonstrates the use of a Decision Tree Classifier for diabetes prediction based on health attributes. You can adapt and modify it for similar classification tasks or experiment with different machine learning algorithms.

If you have any questions or encounter any issues, please feel free to open an issue or contact the project maintainers.

Happy predicting diabetes!
```
