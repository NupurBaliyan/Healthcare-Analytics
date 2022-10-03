# Healthcare-Analytics
Goal You need to find the outcome where the outcome is defined as a favourable outcome is defined as getting a health_score, while in the third format it is defined as visiting at least a stall.

**Data Description**

The problem contains two datasets, Train Data, and Test Data. Model building is to be done on Train Dataset and the Model testing is to be done on Test Dataset. The output from the Test Data is to be submitted in the Hackathon platform

The whole dataset comprises of 6 csv files alongside the data dictionary that contains definitions for each variable

**Health_Camp_Detail.csv** 
        – File containing Health_Camp_Id, Camp_Start_Date, Camp_End_Date and Category details of each camp.

**Train.csv**
        – File containing registration details for all the test camps. This includes Patient_ID, Health_Camp_ID, Registration_Date and a few anonymized variables           as of registration date.

**Patient_Details.csv **
        – This file contains Patient profile details like Patient_ID, Online_Follower, Social media details, Income, Education, Age, First_Interaction_Date, City_Type and Employer_Category

**First_Health_Camp.csv**
       – This file contains details about people who attended the health camp in the first format. This includes Donation (amount) & Health_Score of the person.

**Second_Health_Camp.csv**
       - This file contains details about people who attended the health camp in the second format. This includes the Health_Score of the person.

**Third_Health_Camp.csv**
       - This file contains details about people who attended health camp of the third format. This includes Number_of_stall_visited & Last_Stall_Visited_Number.

**Evaluation Metric**
Your score is the percentage of all correct predictions made by you. This is simply known as accuracy. The best accuracy is 1 whereas the worst is 0. It will be calculated as the total number of two correct predictions (True positive + True negative) divided by the total number of observations in the dataset.

**Submission File Format:**
You should submit a CSV file with exactly 22584 entries plus a header row.
The file should have exactly two columns:
Patient_ID (test set)
outcome (predicting 0 & 1)
