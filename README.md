# Predicting Apartment Prices in Mexico City
## Purpose
The real estate market is a pivotal sector of any economy and understanding the factors that impact property prices can be of high value to both buyers and sellers. The purpose of this project is to create a predictive model that estimates the prices of apartments in Mexico City based on various features such as surface covered, location, and borough. This project is focused on predictive data science and aims to provide insights into the real estate market city of Mexico.
## Data
The data used in this project was obtained from open sources and contains information on properties in Mexico City. The data was stratified into 5 CSV files and was pre-processed to eliminate any missing or irrelevant information. The main columns of interest after the cleaning process include:
* price
* Borough
* Longitude
* Latitude
* Surface Area

## Methodology
The project was done using two notebooks, the first one was used for Preliminary examination and wrangling, while the second was for modeling and deployment. The following methods were used in this project:                                                                                                                                                                                                                                                                         
**Ridge Regression**: Ridge regression is a type of linear regression that includes an additional penalty term in the loss function. The penalty term is the sum of the squares of the regression coefficients multiplied by a regularization parameter (lambda). This a useful tool for handling datasets with a large number of predictors, as it can help to reduce the impact of noise in the data and improve the generalization performance of the model.

**SimpleImputer**: This is used for imputing missing values in a dataset. It replaces missing values with either mean, median, mode, or a constant value depending on the strategy selected.However, it is important to note that imputation may introduce bias into the dataset and should be used with caution.

**OneHotEncoder**: This is used for encoding categorical features into numerical features that can be used in machine learning algorithms.OneHotEncoder is useful when working with machine learning algorithms that require numerical inputs, as it allows categorical data to be represented in a way that the algorithm can understand. However, it is important to note that OneHotEncoder can greatly increase the dimensionality of the dataset, which can be a problem if the number of categories is very large.

## Results
The results of this project can be seen stated below:
* A graphical visualization of the most important boroughs in Mexico City based on the model's predictions. This visualization provides information about boroughs having the highest and lowest predicted apartment prices.

* A function (make_prediction) that takes 4 arguments (surface covered, latitude, longitude, and borough) and returns the model's prediction for an apartment price. This function can be used to make predictions for new apartments based on these four features.

* An interactive widget made with Jupyter widgets, which can be adjusted to see how predicted apartment prices change based on different input values.
 
## Usage
It is important to note that this project is for educational purposes only and the results should not be used for real-world decision making without proper verification and validation.
## Conclusion
In conclusion, this project designed  to create a predictive model for apartment prices in Mexico City using data science techniques. The results of the project provide insights into the real estate market in Mexico City and can be used to make data driven decisions about property investments. This project serves as an example of how data science can be applied to real-world situations and its importance and influence in making data driven decisions.

 
                                                                                                                                                                                                                                             