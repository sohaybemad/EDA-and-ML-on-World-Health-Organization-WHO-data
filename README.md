# EDA-and-ML-on-World-Health-Organization-WHO-data
## Description:
### Main steps of the project:
### Explore the data: 
In this project we will explore The data was collected from World Health Organization (WHO). The data-set related to life expectancy with health factors for 193 countries 
### data preprocessing: 
* 1) Choose only needed columns
* 2) Handling mising values 
* 3) Handling outliers
### Ask some questions and answer them using visualizations : 
Questions asked:
* Does our data contain more develping countries or more developed countries?
* Does the average of the life expectancy vary based on the status of the country?
* Does the average of the life expectancy vary based on the status of the country?
* Does the average of the infant deaths vary based on the status of the country?
* Do you think Total_expenditure will be bigger in the developed countries or the developing countries?¶
* Does the average of schooling years vary based on the status of the country?
* The relation between the two columns (Polio, Diphtheria) and the Life_expectancy column
* Does the number of countries vary per year?
*  how the life expectancy change over years
  
 
### Applying different ML models to predict the Life Expectancy:
models used: Lasso, Ridge , DecisionTree, SVR, and Xgboost
we used the pipeline and GridSearch for hyper parameter tuning the choose the best model to predict our target variable (Life_expectancy)
