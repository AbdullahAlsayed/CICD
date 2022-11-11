# Model Card

For additional information see the Model Card paper: https://arxiv.org/pdf/1810.03993.pdf

## Model Details
This Model is for Building a scalable CICD pipeline for predicting salary based on census dataset 
Continous Deployment is done through heroku
APIs calling is done through FastAPI
Continous Integration is done through Github Action to run flake8 and pytest
This model go through 10 slices to detect the best result coming from which slice and run the final model based on that slice
This model used RandomForestClassifier

## Intended Use
This Model is intended to predict if salary is >50 or <50 

## Training Data
.8 of the data were used for training

## Evaluation Data
.2 of the data were used for evaluating

## Metrics
_Please include the metrics used and your model's performance on those metrics._
metrics used are precision: 0.75, recall: 0.63, f1: 0.69, accuracy: 0.86

## Ethical Considerations
The environment has changed a lot since 1994 -data collection date- so it's not that much accurate to depend on this data 

## Caveats and Recommendations
