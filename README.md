# Professional_Certificate
Portfolio project on optimising a model for real-life data

# Smoke Detector


## EXPLANATION 

The project uses a fire detector dataset that is found on kaggle. It uses a number of sensor measurements to predict whether or not there is a fire present.

## DATA
The dataset that I used was downloaded directly from Kaggle (https://www.kaggle.com/code/dhavalrupapara/smoke-detection-using-machine-learning/input)

## MODEL 
I trained five models for comparison: Logistic Regression; Decision Tree classifier; Random Forest classifier; Support Vector Machine classifier; and Gradient Boost. All models performed exceptionally well, scoring almost 100 %.

## HYPERPARAMETER OPTIMSATION
The only model that benefitted from hyperparameter tuning was the Logistic Regression model, where accuracy, recall and precision were improved as follows:

Before Logistic Regression model hyperparameter tuning
Accuracy: 0.9692639310234712 Recall: 0.9696562534990483 Precision: 0.9870070663323456 

After Logistic Regression model hyperparameter tuning
Accuracy: 0.991218266006706  Recall: 0.994961370507222  Precision: 0.9927382415372584

## RESULTS
The best performances for all five models are as follows:

Model	                    Best Accuracy	      Best Recall	        Best Precision
Logistic Regression	      0.991218266006706	  0.994961370507222	  0.9927382415372584
Decision Tree Classifier	0.9999201660546064	1.0	                0.9998880429914913
Random Forest Classifier	0.9998403321092129	0.9997760609114321	1.0
Support Vector Machine	  0.9993613284368513	0.9998880304557161	0.9992167393980083
Gradient Boosting	        0.9999201660546064	0.9998880304557161	1.0


## CONTACT DETAILS
krishna.seunarine@swansea.ac.uk
