# **STROKE PREDICTION DETAILS**

**[JUMP TO STROKE PREDICTION NOTEBOOK HERE IN GITHUB](https://github.com/RJKool/Project-2---Part-1-Core-/blob/main/STROKE%20PREDICTION.ipynb)**

## **Source of data**
This dataset was pulled from KAGGLE.COM (https://www.kaggle.com/datasets/fedesoriano/stroke-prediction-dataset)

## **Brief description of data**
According to the World Health Organization (WHO) stroke is the 2nd leading cause of death globally, responsible for approximately 11% of total deaths.  This dataset is used to predict whether a patient is likely to get stroke based on the input parameters like gender, age, various diseases, and smoking status. Each row in the data provides relavant information about the patient.

## **What is the target?**
Target prediction is the stroke column.  I aim to predict if a patient has a stroke.

##  **What does one row represent?**
Each row represents a single patient and their health stats.

##  **Is this a classification or regression problem?**
This is a classification problem.

##  **How many features does the data have?**
The dataset has 11 features.

##  **How many rows are in the dataset?**
There are 5,109 rows of data in this dataset and 12 columns.

##  **What, if any, challenges do you foresee in cleaning, exploring, or modeling this dataset?**
Hopefully the dataset will not have any missing values.  I will properly correct any missing values if found.

# **DATA DICTIONARY**
1. ***id:*** unique identifier
2. ***gender:*** "Male", "Female" or "Other"
3. ***age:*** age of the patient
4. ***hypertension:*** 0 if the patient doesn't have hypertension, 1 if the patient has hypertension
5. ***heart_disease:*** 0 if the patient doesn't have any heart diseases, 1 if the patient has a heart disease
6. ***ever_married:*** "No" or "Yes"
7. ***work_type:*** "children", "Govt_jov", "Never_worked", "Private" or "Self-employed"
8. ***Residence_type:*** "Rural" or "Urban"
9. ***avg_glucose_level:*** average glucose level in blood
10. ***bmi:*** body mass index
11. ***smoking_status:*** "formerly smoked", "never smoked", "smokes" or "Unknown"*
12. ***stroke:*** 1 if the patient had a stroke or 0 if not
*Note: "Unknown" in smoking_status means that the information is unavailable for this patient

---
---

# **SPANISH WINE QUALITY**

**[JUMP TO WINE QUALITY NOTEBOOK HERE IN GITHUB](https://github.com/RJKool/Project-2---Part-1-Core-/tree/main)**

## **Source of data**
This dataset was pulled from KAGGLE.COM (https://www.kaggle.com/datasets/fedesoriano/spanish-wine-quality-dataset)

## **Brief description of data**
This dataset is related to red variants of spanish wines. The dataset describes several popularity and description metrics their effect on it's quality. The datasets can be used for classification or regression tasks. The classes are ordered and not balanced (i.e. the quality goes from almost 5 to 4 points). The task is to predict either the quality of wine or the prices using the given data.

## **What is the target?**
Target prediction is the price column.

##  **What does one row represent?**
Each row represents a bottle of wine and many standard wine attributes year produce, price per bottle, country of origin, etc.

##  **Is this a classification or regression problem?**
This is a regression problem since I will be building a model to predict price.

##  **How many features does the data have?**
The dataset has 11 features.

##  **How many rows are in the dataset?**
There are 7,500 rows of data in this dataset and 12 columns total.

##  **What, if any, challenges do you foresee in cleaning, exploring, or modeling this dataset?**
Hopefully the dataset will not have any missing values.  I will properly correct any missing values if found.

# **DATA DICTIONARY**
1. ***winery:*** Winery name
2. ***wine:*** Name of the wine
3. ***year:*** Year in which the grapes were harvested
4. ***rating:*** Average rating given to the wine by the users [from 1-5]
5. ***num_reviews:*** Number of users that reviewed the wine
6. ***country:*** Country of origin [Spain]
7. ***region:*** Region of the wine
8. ***price:*** Price in euros [€]
9. ***type:*** Wine variety
10. ***body:*** Body score, defined as the richness and weight of the wine in your mouth [from 1-5]
11. ***acidity:*** Acidity score, defined as wine's “pucker” or tartness; it's what makes a wine refreshing and your tongue salivate and want another sip [from 1-5]
