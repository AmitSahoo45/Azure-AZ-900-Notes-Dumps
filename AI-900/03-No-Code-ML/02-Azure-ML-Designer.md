### Azure ML Designer: No Code Machine Learning with More Control

#### Overview
- **Azure ML Designer**: A no-code tool within Microsoft Azure for building and customizing machine learning models.
- **Control**: Allows for more hands-on data examination and model building compared to Automated Machine Learning (AutoML).

#### Steps in Using Azure ML Designer

1. **Data Setup**
   - **Drag Data Set**: Import your data set onto the designer canvas.
   - **Examine Data**: Visualize data to understand distributions and characteristics (e.g., histograms for each column).

2. **Data Preparation**
   - **Exclude Columns**: Remove columns that do not positively impact the model’s results.
   - **Exclude Rows**: Remove rows with missing or incomplete data. Be cautious, as this can affect the model's generalizability.
   - **Normalization**: Standardize the range of values in different columns to a common scale (e.g., 0 to 100).

3. **Model Selection and Building**
   - **Choose Model**: Select from dozens of available models based on your specific needs.
   - **Drag and Drop**: Add selected models and data preparation steps to the canvas.

#### Example Workflow
- **Data Source**: Automobile data.
- **Steps**:
  - **Select Columns**: Choose relevant features.
  - **Clean Data**: Exclude irrelevant or problematic data entries.
  - **Normalize Data**: Standardize data ranges.
  - **Data Split**: Divide data into training and evaluation sets.
  - **Model Selection**: Choose a linear regression model.
  - **Train and Evaluate**: Train the model and assess its performance.

#### Benefits of Azure ML Designer
- **No Coding Required**: Build and customize models without writing code.
- **Hands-On Control**: Directly interact with and prepare data.
- **Visualization Tools**: Easily visualize and understand data characteristics.
- **Customization**: Flexibly choose and modify models and data preparation steps.

#### Example Visualization
- **Workflow**:
  - **Automobile Data**: Initial data source.
  - **Select Columns**: Identify important features.
  - **Clean Data**: Exclude unnecessary columns and rows.
  - **Normalize Data**: Adjust ranges for consistency.
  - **Split Data**: Separate into training and validation sets.
  - **Linear Regression Model**: Apply the chosen model.
  - **Evaluate**: Assess model accuracy and effectiveness.

### Summary
- **Azure ML Designer**: Provides a no-code environment for creating and customizing machine learning models.
- **Steps**: Involve data setup, preparation, model selection, and evaluation.
- **Control and Customization**: Offers more control compared to AutoML, allowing for detailed data examination and model tuning.
- **Benefits**: Combines ease of use with flexibility, making it suitable for users who want to build models without coding but with greater control over the process.

### Next Steps
- **Live Demonstration**: A practical demonstration of using Azure ML Designer to build and evaluate a machine learning model.