# Breast Cancer Prediction with Decision Tree Classifier

This Python script demonstrates the implementation of a Decision Tree Classifier for predicting breast cancer outcomes. 

**Key Features:**

* **Data Loading and Preprocessing:**
    - Loads breast cancer data from a CSV file.
    - Cleans the data by removing rows with missing values.
    - Preprocesses the data by:
        - Encoding categorical variables using LabelEncoder.
        - Scaling numerical features using StandardScaler.
* **Model Training and Evaluation:**
    - Splits the data into training and testing sets.
    - Performs hyperparameter tuning using Grid Search with Cross-Validation to find the best model configuration.
    - Trains the Decision Tree Classifier with the optimal hyperparameters.
    - Evaluates the model's performance using accuracy, classification report, and confusion matrix.
* **Visualization:**
    - Visualizes the trained decision tree using `plot_tree()` for better understanding of the model's decision-making process.

**Installation:**

1. Make sure you have the following libraries installed:
   - pandas
   - scikit-learn
   - matplotlib

   You can install them using pip:

   ```bash
   pip install pandas scikit-learn matplotlib
