# Project Overview
## 1. Predicting heart disease 
---

### 📝 About the Project  
In this project, we will try to predict heart disease based on patient medical metrics.
---

### ✨ Notebook logic
We will go through the 6-step Machine Learning model framework in the [notebook](https://github.com/emmanguyen102/Machine-Learning-portfolio/blob/main/regression/Random_forest_regression_problem.ipynb)
![Screenshot 2025-01-15 at 14 00 25](https://github.com/user-attachments/assets/e506b7d9-162b-4265-aecb-6efa040ab20d)

1. Identify the problem:
This is classification problem of finding whether the patient has heart disease.

2. Dataset: The dataset can be found [License]([#license](https://www.kaggle.com/datasets/sumaiyatasmeem/heart-disease-classification-dataset)). 

3. Evaluation:
The initial threshold is 95% accuracy.

4. Features:
We will first create a data dictionary as follows.

- age: age in years
- sex: 1 = male; 0 = female
- cp: chest pain type
    - 0: Typical angina: chest pain related decrease blood supply to the heart
    - 1: Atypical angina: chest pain not related to heart
    - 2: Non-anginal pain: typically esophageal spasms (non heart related)
    - 3: Asymptomatic: chest pain not showing signs of disease
- trestbps: resting blood pressure (in mm Hg on admission to the hospital)
anything above 130-140 is typically cause for concern
- chol: serum cholestoral in mg/dl
    - serum = LDL + HDL + .2 * triglycerides
    - above 200 is cause for concern
- fbs: fasting blood sugar > 120 mg/dl (1 = true; 0 = false)
'>126' mg/dL signals diabetes
- restecg - resting electrocardiographic results
    - 0: Nothing to note
    - 1: ST-T Wave abnormality
can range from mild symptoms to severe problems
signals non-normal heart beat
    - 2: Possible or definite left ventricular hypertrophy
Enlarged heart's main pumping chamber
- thalach: maximum heart rate achieved
- exang: exercise induced angina (1 = yes; 0 = no)
- oldpeak: ST depression induced by exercise relative to rest looks at stress of heart during excercise unhealthy heart will stress more
- slope: the slope of the peak exercise ST segment
    - 0: Upsloping: better heart rate with excercise (uncommon)
    - 1: Flatsloping: minimal change (typical healthy heart)
    - 2: Downslopins: signs of unhealthy heart
- ca: number of major vessels (0-3) colored by flourosopy
colored vessel means the doctor can see the blood passing through
the more blood movement the better (no clots)
- thal: thalium stress result
    - 1,3: normal
    - 6: fixed defect: used to be defect but ok now
    - 7: reversable defect: no proper blood movement when excercising
- target: have disease or not (1=yes, 0=no) (= the predicted attribute)

5. Modelling:
Model chosen is Logistic Regression. 

6. Experiments:
- Tuning hyperparameters to get the best fit parameters to train the model. 
- Feature importance





