

![Picture of ocean](https://github.com/vilmahietala/images/blob/master/ocean.png?raw=true)



 # Titanic - Machine Learning from Disaster


Taking part in the classical [Kaggle's Titanic ML Competition.](https://www.kaggle.com/competitions/titanic) The aim is to use machine learning to create a model that predicts which passengers survived the Titanic shipwreck.

## Results

During the training phase, I achieved the following accuracy rates:

 - A maximum of 85% correct results with the DecisionTreeClassifier.
 - 84% correct results with the LogisticRegression model.
  - 81% correct results with the RandomForestClassifier.

### Testing phase
I conducted five iterations with the test data, submitting the results to Kaggle after each run. The accuracy scores varied between 76% and 79%, with a mean accuracy of 77.90%.

## Methods

### Data Exploration (explore_training_data file):
- Explored and visualized the training data using common exploratory methods to gain a better understanding of its structure and characteristics.
- Looked for relevant information and potential issues within the data.
### Prepared the data (prepare_and_predict file):
  - Dropping irrelevant columns.
  - Converting textual data into numerical format.
  - Handling NaN values and outliers.
  - Performing feature engineering.
  - Scaling the data to ensure all features have a similar range.

### Model Selection (prepare_and_predict file):
  - Tested individual models and evaluated their performance.
  - Decided to use a voting classifier that combines predictions from multiple models (DecisionTreeClassifier, LogisticRegression, RandomForestClassifier) to improve overall prediction accuracy.
