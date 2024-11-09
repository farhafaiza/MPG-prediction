# MPG-prediction
Regression analysis Auto MPG Dataset
## Overview
Regression analysis is used in this project to forecast an automobile's miles per gallon (MPG) based on a number of characteristics, including horsepower, weight, and displacement. In order to ascertain whether regression model produces superior predictions, this investigation contrasts two models: Linear Regression and Random Forest Regression, using Python and well-known data science modules. According to the results, the Random Forest model predicts MPG more accurately than Linear Regression.
## Dataset
The Auto MPG dataset, which includes details on fuel usage and characteristics of different automobile models, was utilized for this study. Key features include:
1. MPG (miles per gallon)
2. Cylinders
3. Displacement
4. Horsepower
5. Weight
6. Acceleration
7. Model Year
8. Origin
9. Car_name
## Target Variable
MPG = Miles Per Gallon which is the fuel consumption value for car
## Installation and Setup
1. Clone this repository to your local machine:
```
git clone https://github.com/farhafaiza/auto-mpg-regression.git
```
2. Navigate to the project directory:
```
cd auto-mpg-regression
```
3. Install the required packages

## Libraries Used
- Scikit-Learn
- Pandas
- NumPy
- Matplotlib
- Seaborn
## EDA
To learn more about the connections between MPG and other vehicle characteristics, an exploratory data analysis (EDA) was carried out. Among the data visualizations are:
- Used pair plots to see how characteristics relate to one another.
- To investigate feature correlations, applied a correlation matrix.
- To comprehend the spread and distribution of important properties, distribution graphs is used.
## Models Used
1. Linear Regression
2. Random Forest Regression
## Model Evaluation
R-squared (R²) and Mean Absolute Error (MAE) were two measures used to assess the performance of both models. Random Forest Regression outperformed Linear Regression in terms of prediction accuracy based on these criteria, suggesting that it is a superior fit for this dataset.
## Key Results
The baseline model, linear regression, has a reasonable level of prediction accuracy.
As it better suited the non-linear correlations in the data, Random Forest Regression outperformed Linear Regression.
## Usage
- After loading the dataset, do out data preparation (categorical variable encoding, managing missing values, etc.).
- Utilizing the assessment metrics, run the models and compare how well they perform.
- Interpret model performance and feature important insights by visualizing the findings.
## Conclusion
The Random Forest approach excelled the Linear Regression model in predicting MPG, better capturing complex correlations in the data. This study emphasizes Random Forest as a reliable option for non-linear datasets and illustrates the significance of model selection in regression tasks.
## Suggestions
For any suggestions or opinion, please reach out to me at forhathunnesa@gmail.com.
