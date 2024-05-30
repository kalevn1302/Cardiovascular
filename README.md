# Cardiovascular 
# Problem Statement :

-The dataset is from an ongoing cardiovascular study on residents of the town of Framingham, Massachusetts. 
-The classification goal is to predict whether the patient has a 10-year risk of future Coronary Heart Disease (CHD). 
-The dataset provides the patients’ information. It includes over 4,000 records and 15 attributes. Each attribute is a potential risk factor. 
-There are both demographic, behavioral, and medical risk factors.

# Libraries Used :
1. Numpy
2. Pandas
3. Matplotlib
4. seaborn
5. sklearn
      
# Exploratory Data Analysis(EDA) 
- Analysing  the data with the help of EDA.
- In this EDA Graphs are plotted like Histplot , Countplot , Barplot , Heatmap , Pairplot , etc.

# Histplot :
- In histplot gets the count of TenYearCHD Patients (CHD - Coronary Herat Disease) and also gets the count of heartRate.

![Screenshot 2024-05-30 160220](https://github.com/kalevn1302/Cardiovascular/assets/171181024/cf30635d-7626-4a4f-82ea-ea4e7dc4b6eb)

![Screenshot 2024-05-30 160511](https://github.com/kalevn1302/Cardiovascular/assets/171181024/699ee925-79e8-4920-bcbf-bfd7dff7cda4)

# Countplot : 
- Countplot gets the count of patients by gender 

![Screenshot 2024-05-30 160634](https://github.com/kalevn1302/Cardiovascular/assets/171181024/03c32b91-cca3-4110-aab2-d161130a18bd)

# Barplot : 
- Barplot gets the count of patients by prevalentHyp(prevalentHyp-if the patient has history of Hypertension) ,etc.

![Screenshot 2024-05-30 160734](https://github.com/kalevn1302/Cardiovascular/assets/171181024/3013cd62-a6ce-454b-bc08-13409a5bc409)

# Handling Missing Values :

- For handling the missing values here use the fillna() for replaces the null values with a specified values 
dropna() used for removes the rows that contains null values . After that there is not any null value. 


# Training and Testing Data 
 - For training and testing data x and y variables are used in it .


# Algorithms Used : 

1. Logistic Regression
   
![Screenshot 2024-05-30 161550](https://github.com/kalevn1302/Cardiovascular/assets/171181024/8014df14-ec1e-4117-9099-539c28e22ed6)

3. Decision Tree
   
5. KNN 

# Feature Scalling :

- For the feature scalling here used the Normalization and Standardization technique. 

# Model Training :
- After fetaure scaling madel tarining with Data Evaluation with the Algorithms  .
- In model training we can see the Accuracy of our model by using the various algorithms.
-But in this model our model shows the 100% accuracy because of imbalance data so , thats why we have to convert the "Imbalance data into Balance data" in further process.

# Converting Imbalance data into Balance Data :
- Converting the Imbalance data into Balance Data with using "SMOTE" technique. for the Over_Sampling .

--After Balancing the data our model predicts the proper Accuracy of the Disease.--

# Final Output :

# As result shows the Random Forest Model performs well with 75% accuracy and 23% recall

![Screenshot 2024-05-30 130029](https://github.com/kalevn1302/Cardiovascular/assets/171181024/415f9f67-0052-46e1-8e93-320558708dfb)




 
