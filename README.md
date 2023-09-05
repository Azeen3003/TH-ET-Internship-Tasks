# TH-ET-Internship-Tasks
### This is a repository where I'll be uploading tasks/projects assigned to me during my Data Analytics Internship at TechnoHacks EduTech.

1. Task 1 - **Data Cleaning** - For this task, I had to download the iconic Titanic dataset from Kaggle and clean it. This dataset is not only historically significant but also a rich source of insights waiting to be uncovered. I had two approaches for this task. One was to remove missing values by deletion. I deleted the column where missing values were more than 75% and then used the ``` dropna() ```
 method to remove the null values. This resulted in the size reduction of the dataset. My other approach was to impute the missing values. I filled the missing values using ```fillna()```. I filled the missing values in the cabin column with ```'unknown'```, filled the missing values in the age column with the mean age and filled the missing values in the Embarked column with the most common value. This did not result in the reduced sixe of the dataset and the number of rows and columns remained intact.
   
