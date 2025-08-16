# Air Quality Analysis and AQI Prediction

## Description
This project analyzes the relationship between various air pollutants and the Air Quality Index (AQI). Using a dataset of daily air quality measurements from various cities, this project aims to predict the AQI bucket (e.g., "Satisfactory", "Moderate", "Poor") based on the concentrations of different air components. The analysis involves data inspection, cleaning, and the application of several machine learning models to find the most accurate predictor.

## Data Cleaning
The initial dataset contained a significant number of missing values and outliers. The following steps were taken to clean the data:

Missing Values: Missing data points for air pollutant concentrations and AQI were imputed using the median value for each respective city. This approach was chosen because the data distributions were skewed.

Outliers: Outliers in the dataset were identified and treated to ensure they did not disproportionately affect the performance of the machine learning models.

## Machine Learning Models
Several classification models were evaluated to predict the AQI_Bucket. The models and their respective accuracies are as follows:

- K-Nearest Neighbors: 84% accuracy
- Support Vector Machine: 92% accuracy
- Logistic Regression: 95% accuracy
- Random Forest Classifier: 98% accuracy

Based on these results, the Random Forest Classifier was selected as the final model for this project due to its superior performance.

## Installation
To run this project, you will need Python and the following libraries installed:
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

You can install these packages using pip:

pip install pandas numpy matplotlib seaborn scikit-learn

How to run: 
- Add dataset city.csv
- Add the ipnyb file
- Run the Jupyter Notebook to see the analysis and model training:


Contributing
Contributions are welcome! If you have suggestions for improvements, please open an issue or submit a pull request.
