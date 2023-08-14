# <p align="center"> Chronic_Kidney_Disease_Data
# <p align="center"> ![knn](https://user-images.githubusercontent.com/100838547/224485513-52314ed9-468b-4424-a944-23fb1b0c546e.png)

In this project, we worked with a data set that was collected to help doctors diagnose chronic kidney disease (CKD). Each row in the data set represents a single patient who was treated in the past and whose diagnosis is known. For each patient, we have a bunch of measurements from a blood test. We’d like to find which measurements are most useful for diagnosing CKD, and develop a way to classify future patients as “has CKD” or “doesn’t have CKD” based on their blood test results.

## Process
### Step 1: Data Preparation
* I import the relevant python libraries needed to carry out this analysis and carried out data cleaning by renaming the Blood Glucose Random" as "Glucose".
* I used EDA( Exploratory data analysis) to checked the shape of the data and check the data types. I run the code to know the number of patients with chronic kidney disease and the patients without the disease. In the notebook "0" was used to represent patient without chronic kidney disease and "1" was used to represent patients with the disease. 
* From our analysis, there are 115 patients without chronic kidney disease and 43 patients with the disease.
* I used a scatter plot to visualize the relationship between Hemoglobin  and Glucose.

### Step 2: Model
The scatter plot visualization suggest that K-NN classifier would be pretty much accurate. The K-nearest neighbor algorithm is a supervised learning classifier which uses proximity to make classifications or predictions about the grouping of an individual data point.

### Outcomes
The result show that the future patient does not have chronic kidney disease

### View this project: [click the link](https://github.com/ellaclauz/Chronic_Kidney_Disease_Data/blob/main/CKD.ipynb)

