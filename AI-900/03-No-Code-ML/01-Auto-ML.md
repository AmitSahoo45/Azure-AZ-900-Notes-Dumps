### No Code Machine Learning in Azure

#### Overview
- **Azure Machine Learning**: A cloud-based service that simplifies data preparation, model training, and deployment of predictive services.
- **No Code Machine Learning**: Involves tools that do not require programming skills, focusing on automated processes and drag-and-drop interfaces.

#### Automated Machine Learning (AutoML)
- **Definition**: A no-code approach where you set up AutoML with your data and it automatically finds the best algorithm.
- **Process**:
  - **Data Setup**: Define and configure your data set.
  - **Computation Configuration**: Set parameters for the AutoML process.
  - **Iteration and Evaluation**: AutoML tries different algorithms and setups, evaluating each iteration to find the best model.
- **Example**:
  - **Data Set**: Input data is evaluated against multiple algorithms.
  - **Results**: Models are ranked based on their evaluated scores (e.g., 95%, 76%, 53%).

#### Machine Learning Designer
- **Definition**: A drag-and-drop interface within Azure Machine Learning for building models without coding.
- **Process**:
  - **Data Source Setup**: Import and define your data set.
  - **Data Visualization and Cleaning**: Inspect and clean the data (e.g., remove columns, exclude rows with bad or missing data).
  - **Data Normalization**: Adjust data columns to suitable formats (e.g., converting specific ages to age ranges).
  - **Model Building**: 
    - **Drag Data Set**: Onto the designer canvas.
    - **Modify Data**: Clean and normalize the data.
    - **Data Split**: Divide data into training and evaluation sets.
    - **Model Selection**: Choose and drag the desired model (e.g., linear regression) onto the canvas.
    - **Train and Evaluate**: Train the model and evaluate its performance.

#### Production Deployment
- **Transition to Production**:
  - **Modify Training Model**: Convert the training model into a production model by removing the evaluation and data splitting steps.
  - **Data Source**: Use live data sources (e.g., Web service) instead of training data.

#### Visual Workflow Example
- **Steps**:
  - **Data Import**: Load and inspect data.
  - **Data Cleaning**: Remove unwanted columns and rows.
  - **Normalization**: Adjust data formats.
  - **Data Splitting**: Divide into training and validation sets.
  - **Model Selection**: Choose and configure the algorithm.
  - **Model Training**: Train the model.
  - **Model Evaluation**: Assess the model's performance.
  - **Production Deployment**: Implement the model with live data sources for real-time predictions.

### Summary
- **Azure Machine Learning**: Offers no-code options like AutoML and Machine Learning Designer to simplify the machine learning process.
- **Automated Machine Learning (AutoML)**: Automatically finds the best algorithm for your data through iterative testing.
- **Machine Learning Designer**: A drag-and-drop interface that allows building and deploying models without coding.
- **Production Deployment**: Transition models from training to production by modifying data sources and removing evaluation steps.

#### Next Steps
- **Demo**: A practical demonstration of no-code machine learning using Azure Machine Learning Designer and AutoML to build and deploy models.