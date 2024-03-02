
## Usage
1. Clone this repository to your local machine.
2. Navigate to the project directory.
3. Run the code in a Python environment. You can use Jupyter Notebook or any Python IDE.
4. Ensure that the file "London.csv" is in the same directory as your code.

## Description of Files
- `README.md`: Provides an overview of the project, instructions for usage, and a brief explanation of the code.
- `London.csv`: Dataset containing London property data.
- `model.py`: Python script containing the code for sentiment analysis.

## Explanation of Code
1. **Data Loading**: 
   - The code loads the dataset from the file "London.csv" using pandas' `read_csv()` function.

2. **Data Preprocessing**:
   - It performs basic data preprocessing steps such as dropping unnecessary columns, handling missing values, and encoding categorical variables using LabelEncoder.

3. **Data Visualization**:
   - The code creates visualizations to explore the data, including a correlation heatmap and a scatter plot to visualize the relationship between the area size and property price.

4. **Model Building**:
   - It builds two regression models: Linear Regression and Random Forest Regression, to predict property prices based on various features.

5. **Model Evaluation**:
   - The code evaluates the performance of the regression models using the coefficient of determination (R^2) score.

6. **Hyperparameter Tuning**:
   - It uses GridSearchCV to perform hyperparameter tuning for the Random Forest Regression model to improve its performance.

Overall, the code aims to analyze London property data, preprocess the data, visualize relationships between variables, build regression models, and evaluate their performance. It also demonstrates the process of hyperparameter tuning to optimize model performance.



