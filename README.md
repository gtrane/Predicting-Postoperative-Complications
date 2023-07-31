# Predicting-Postoperative-Complications

Worked in a team applying classification modeling in Orange software to predict post-operative complications. Implimented a Random Forest model to minimize hospital costs in identifying a vulnerable patient population.
<img width="1036" alt="Screenshot 2023-05-04 at 10 03 42 AM" src="https://user-images.githubusercontent.com/116750192/236248579-8efccfd1-cdb1-4665-828b-fb0bd215959f.png">

#### Project Summary
The goal of this project was to determine the best model to classify an occurrence of a post-operative complication following general surgery. Data was originally collected by Sessler et al. in a study titled “Operation Timing and 30-Day Mortality After Elective General Surgery”. This dataset consisted of a single CSV file with 14,635 patients who underwent elective general surgery. The dataset has information on the patient’s age, gender, race, body mass index (BMI), comorbidities, several surgical indices, and the surgical timing predictors. The full list of 25 features are detailed in the Surgery Timing Data Dictionary file. 

Six classification models were investigated (neural network, logistic regression with regularization, k-nearest neighbors, classification tree, random forest, gradient boosted ensemble) with 10-fold cross validation on training data before determining to move forward with the Random Forest on testing data.

The file 'classificationforestProject.ows' documents the Random Forest and Gradient Boosting models. Logloss values were investigated with a feature constructor, and the gradient boosting model had unreliable predictions with high logloss values in older populations (75+). High logloss wasn't seen in the Random Forest model and was thus determined to be the best model.

#### Key Takeaways
Using this model, a hospital could identify a vulnerable patient population that is at risk of developing a complication following surgery. Implimenations of our model include increased monitoring, follow-up appointments, medication management, and an emphasis on proper patient and caregiver education following surgery. 
