# Predicting-Postoperative-Complications
Classification modeling in Orange software to implement machine learning techniques. Used Random Forest to minimize hospital costs in identifying a vulnerable patient population.
<img width="1036" alt="Screenshot 2023-05-04 at 10 03 42 AM" src="https://user-images.githubusercontent.com/116750192/236248579-8efccfd1-cdb1-4665-828b-fb0bd215959f.png">

The goal of this project was to determin the best model to classify a dataset. My team chose to investigate the occurrence of postoperative complications following a general surgery. Our data was originally collected by Sessler et al. in their study titled “Operation Timing and 30-Day Mortality After Elective General Surgery”. Our dataset consists of a single CSV file that includes the records of 14,635 patients who underwent elective general surgery. Specifically, the dataset has information on the patient’s age, gender, race, body mass index (BMI), comorbidities, several surgical indices, and the surgical timing predictors. The full list of 25 features are detailed in the Surgery Data Dictionary file. 

The Data Science Project Write-Up and the powerpoint detail my team's findings, with our Powerpoint geared toward a managerial audience. We determined a Random Forest model, with a high weight on recall, as our best model. Using this model, a hospital can identify a vulnerable patient population that is at risk of developing a complication following surgery. Implimenations of our model include increased monitoring, follow-up appointments, medication management, and an emphasis on proper patient and caregiver education following surgery. 
