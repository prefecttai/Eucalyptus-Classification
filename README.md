# Eucalyptus Classification for Soil Conservation

This project analyzes different Eucalyptus species and predicts their effectiveness for soil conservation and fertility based on various attributes.

## Dataset
The dataset contains 738 observations of 13 different Eucalyptus species planted at experimental sites in New Zealand over 12 years. It has 20 attributes including physical metrics, climate data, and categorical evaluations of each tree. The target variable is the "Utility" level rating tree quality for soil conservation as None, Low, Average, Good or Best.  

## Methods
The analysis workflow includes:

- Data cleaning 
- Visualizing target distribution  
- Preprocessing - imputation, converting data types
- Feature selection methods - Chi squared, Learning Vector Quantization, Recursive Feature Elimination, Random Forest Importance, Information Gain  
- Classification models - Naive Bayes, KNN, Decision Trees, Neural Network
- Evaluation using ROC AUC, accuracy, precision, recall, F1, MCC

## Results  
The best model uses Recursive Feature Elimination for feature selection and Naive Bayes classification, achieving a ROC AUC score of 0.830. The top predictive attributes are survival rate, insect resistance, rainfall, and diameter breast height.

## Usage
The full code can be found in the Jupyter notebook. It requires Python and common data science libraries like Pandas, Matplotlib, Scikit-learn, etc.

## Credits  
The dataset is from OpenML: https://www.openml.org/search?type=data&status=active&id=188
