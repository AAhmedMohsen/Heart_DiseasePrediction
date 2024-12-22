Problem:
In this project, we delve into a dataset encapsulating various health metrics from heart patients, including age, blood pressure, heart rate, and more. Our goal is to develop a predictive model capable of accurately identifying individuals with heart disease. Given the grave implications of missing a positive diagnosis, our primary emphasis is on ensuring that the model identifies all potential patients, making recall for the positive class a crucial metric.
Objectives:
Explore the Dataset: Uncover patterns, distributions, and relationships within the data.

Conduct Extensive Exploratory Data Analysis (EDA): Dive deep into bivariate relationships against the target.

Preprocessing Steps:
1-Remove irrelevant features
2-Address missing values
3-Treat outliers
4-Encode categorical variables
5-Transform skewed features to achieve normal-like distributions

Model Building:-
1-Establish pipelines for models that require scaling.
2-Implement and tune classification models including KNN, SVM, Decision Trees, and Random Forest.
3-Emphasize achieving high recall for class 1, ensuring comprehensive identification of heart patients.

Evaluate and Compare Model Performance: Utilize precision, recall, and F1-score to gauge models' effectiveness.

Data description:

Variable	Description

age	Age of the patient in years

sex	Gender of the patient (0 = male, 1 = female)

cp	Chest pain type:
        0: Typical angina
        1: Atypical angina
        2: Non-anginal pain
        3: Asymptomatic

trestbps  Resting blood pressure in mm Hg

chol	  Serum cholesterol in mg/dl

fbs	Fasting blood sugar level, categorized as    above 120 mg/dl (1 = true, 0 = false)

restecg	Resting electrocardiographic results:
        0: Normal
        1: Having ST-T wave abnormality
        2: Showing probable or definite left ventricular hypertrophy

thalach	Maximum heart rate achieved during a stress test

exang	Exercise-induced angina (1 = yes, 0 = no)

oldpeak	ST depression induced by exercise relative to rest

slope	Slope of the peak exercise ST segment:
        0: Upsloping
        1: Flat
        2: Downsloping

ca	Number of major vessels (0-4) colored by fluoroscopy

thal	Thalium stress test result:
        0: Normal
        1: Fixed defect
        2: Reversible defect
        3: Not described

target	Heart disease status (0 = no disease, 1 = presence of disease)

