## Overview
This project uses Machine Learning (ML) to make predictions on a binary classification target for a telecommunications company. The information came from a dataset provided on kaggle from SyriaTel. Models are used to make the best predictions to find out why customers have churned.(left the company)


## Business Problem
SyriaTel wants to reduce the amount of money lost by checking what are the factors that have made consumers churn. This analysis can help predict which customers have the possibility of churning and find a way to retain them for the future.


## Data Understanding
The dataset was from the SyriaTel dataset. It contained the following:

- 3333 rows of data
- 21 columns that included the target column

The target was churn which included whether a customer had churned or not. The goal was to find out what caused the customers to churn.


## Modeling
The final chosen model was a Random Forest Classifier which had class weights that balanced the data as the data was imbalanced. The primary score that was of focus was Recall. The score reached for recall was 80%.


## Evaluation
The confusion matrix shows the results of the final Random Forest Classifier.
![](images/Screenshot%202022-06-29%20214044.png)

This is a snippet of the results of the important features of the model.
![](images/Screenshot%202022-06-29%20214935.png)


## Conclusion
After working with several models to predict the outcomes of churn data, the final model made predictions and showed the important factors that affect customer churn in the company. The top 3 features that the model stated were:


- Customers who make multiple customer service calls
- Customers’ total day charges
- Customers’ total day minutes

The company should focus on customers who fall into one, two or even all of these categories and develop strategies to retain these customers. 

## For More Information
See the full analysis in the Jupyter Notebook or review this presentation.

For additional info, contact Jonathan Roman at jonathan.roman1213@gmail.com
