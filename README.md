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
#### Exploratory Data Analysis
##### Binary Data pie plots:
##### ![logistic bin plots](https://user-images.githubusercontent.com/86224563/133209520-e2b15993-a5fc-4496-9ce9-0492d551f4a9.PNG)
##### Distribution plots:
##### ![logistic histograms](https://user-images.githubusercontent.com/86224563/133210905-168120ef-8efa-4b9e-870d-5dc23d6751bf.png)
### Conclusions of the Regression Model
##### Contributions of the features:
##### ![logistic Contributions](https://user-images.githubusercontent.com/86224563/133209750-3ef6ffab-20d1-4a9f-89ea-8e72c75a61f5.PNG)
##### Sex, smoking, platelets, high blood pressure, diabetes, creatinine phosphokinase and anaemia doesnt contribute much as compared to other Features to the model.
