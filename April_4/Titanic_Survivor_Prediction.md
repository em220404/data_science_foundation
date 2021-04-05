## Titanic Survivor Prediction



### Objective:

- Predict each passenger's survival rate

----



### Data Explore

- No actual changes to the dataset
- Investigate over the columns and look for important features
  - Column datatypes
  - Null values: how to fill them?
  - Visualization



### Data Wrangle & Transform

Purpose: 

- Drop unnecessary features
  - `Ticket`, `Cabin` 
- Fill in null values
  - `Age`: by prediced values from `Sex`, `Pclass`
- Continuous ordinal values (banding)
  - `Age`
  - `Fare`
  - `SibSp`
- Categorical value -> Ordinal values
  - Sex: Male, Female -> 1, 0
  - Embarked



### Data Modelling (fitting & predicting)

- Regresssion
  - sci-kit learn: LogisticRegression Model
  - Random Forest Classifier Model
- Training Data: train the model
  - Hypter tuning
- Test Data: fit the model
  - Look for accuracy
- Model's accuracy highly depends on the **quality of the processed data**, **efficiency of the model parameters**
- gender_submission.csv: Kaggle

