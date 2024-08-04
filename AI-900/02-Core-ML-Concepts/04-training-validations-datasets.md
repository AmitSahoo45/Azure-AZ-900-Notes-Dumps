### Core Machine Learning Concepts

#### Data Preparation
1. **Data Collection and Cleaning**
   - Gather a substantial amount of data (e.g., a million rows).
   - Clean and preprocess the data for consistency and accuracy.

2. **Data Splitting**
   - **Training Set**: Typically half of the data, used to train the model.
   - **Validation/Test Set**: The other half, used to validate and test the model.
   - **Random Splitting**: Ensure the split is random and representative of the entire dataset to avoid bias (e.g., mix of gender, age, smokers, non-smokers).

#### Model Selection
1. **Algorithm Categories**
   - **Regression**: Predicts continuous values (e.g., life expectancy, prices).
   - **Classification**: Categorizes data (e.g., is it an apple or a pear?).
   - **Clustering**: Finds structure in data without labels (e.g., customer segmentation).

2. **Using Azure Machine Learning**
   - Azure provides various algorithms for different tasks.
   - **Cheat Sheets**: Help determine the best algorithm for the task (e.g., regression for predicting values, clustering for discovering structure).

#### Model Training and Evaluation
1. **Training the Model**
   - Train the model using the training dataset with chosen algorithm(s).
   - **Experimentation**: Run multiple algorithms to find the best fit.

2. **Evaluating the Model**
   - **Mean Square Error (MSE)**: Used for regression models.
     - Measures the difference between predicted and actual values.
     - Calculation: Square the difference between predicted and actual values (larger differences are penalized more).
   - **Classification Evaluation**: Focuses on accuracy and precision.
     - **True Positives**: Correctly identified positive cases.
     - **False Positives**: Incorrectly identified positive cases.
     - **True Negatives**: Correctly identified negative cases.
     - **False Negatives**: Incorrectly identified negative cases.
   - **Accuracy vs. Precision**:
     - **Accuracy**: Overall correctness.
     - **Precision**: Correctness of positive predictions.

3. **Example Metrics**:
   - **Regression**: Mean Square Error (MSE) indicates the average squared difference between predicted and actual values.
   - **Classification**: Measures how often the model is correct (accuracy) and the reliability of positive predictions (precision).

#### Practical Considerations
1. **Choosing Features**:
   - **Relevant Features**: Select features that significantly impact the prediction (e.g., smoking status, age for life expectancy).
   - **Irrelevant Features**: Exclude features that do not impact the prediction (e.g., first and last name).
   - **Ethical Considerations**: Ensure feature selection aligns with ethical standards (e.g., avoiding bias based on income or gender).

2. **Continuous Improvement**:
   - **Model Tuning**: Adjust model parameters and features based on validation results.
   - **Re-evaluation**: Continuously test and refine the model to maintain accuracy and relevance.

### Summary
- **Data Preparation**: Collect, clean, and split data into training and validation sets.
- **Model Selection**: Choose appropriate algorithms for regression, classification, or clustering tasks.
- **Model Training**: Train models using training data and select the best algorithm through experimentation.
- **Model Evaluation**: Use metrics like MSE for regression and accuracy/precision for classification to evaluate model performance.
- **Feature Selection**: Carefully choose relevant and ethical features for the model.
- **Continuous Improvement**: Regularly tune and re-evaluate the model for optimal performance.