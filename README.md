## Heart Failure Prediction
- A logistic Regression model using sklearn 
- Predicts whether the person's heart has failed or not using his/her clinical reports during the follow up period
### Description of the dataset:
| Feature                       |  Explanation                                    |
|:------------------------------|:------------------------------------------------|
| Age                           | Age of the patient                              | 
| Anaemia                       | Decrease of red blood cells or hemoglobin       | 
| High blood pressure           | If a patient has hypertension                   | 
| Creatinine phosphokinase (CPK)| Level of the CPK enzyme in the blood            | 
| Diabetes                      | If the patient has diabetes                     | 
| Ejection fraction             | Percentage of blood leaving                     | 
| Sex                           | Woman or man                                    | 
| Platelets                     | Platelets in the blood                          | 
| Serum creatinine              | Level of creatinine in the blood                | 
| Serum sodium                  | Level of sodium in the blood                    | 
| Smoking                       | If the patient smokes                           | 
| Time                          | Follow-up period                                | 
| DEATH_EVENT                   | If the patient died during the follow-up period | 
##### The dataset can be found on [kaggle](https://www.kaggle.com/andrewmvd/heart-failure-clinical-data).
### Exploratory Data Analysis
- Binary Data pie plots:
##### ![fixed pie](https://user-images.githubusercontent.com/86224563/135388398-8a5f9d17-35d7-4cd0-8507-5f98bb4edb3d.PNG)
-About 31% patients' heart failed during the follow up period.</br>
-The dataset doesn't seem to be balanced between male and female patients.
- Distribution plots:
##### ![logistic histograms](https://user-images.githubusercontent.com/86224563/133210905-168120ef-8efa-4b9e-870d-5dc23d6751bf.png)
##### The disctribution plots shows where the features are most populated at.
### Conclusions of the Logistic Regression Model
- Contributions of the features:
##### ![logistic Contributions](https://user-images.githubusercontent.com/86224563/133209750-3ef6ffab-20d1-4a9f-89ea-8e72c75a61f5.PNG)
##### Sex, smoking, platelets, high blood pressure, diabetes, creatinine phosphokinase and anaemia doesnt contribute much as compared to other Features to the model.
- Accuracy on train and test data:
##### ![logistic accuracy](https://user-images.githubusercontent.com/86224563/133214465-3953cfd7-7cff-4784-be55-6fdaeed12147.PNG)
##### The model seems to be good enough with predictions.
- Confusion Matrix:
##### ![logistic confusion matrix](https://user-images.githubusercontent.com/86224563/133214548-714615cc-0ebf-4c1a-b135-485402ed4145.PNG)
