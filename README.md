# Project: Decision Tree for Classification

# Problem
Apply decision tree model to identify heart disease

# Data Columns
- **age**, **Float**
- **sex** - **Category**
  - 0 = female
  - 1 = male
- **cp**, chest pain, **Category**
  - 1 = typical angina,
  - 2 = atypical angina,
  - 3 = non-anginal pain,
  - 4 = asymptomatic
- **restbp**, resting blood pressure (in mm Hg), **Float**
- **chol**, serum cholesterol in mg/dl, **Float**
- **fbs**, fasting blood sugar, **Category**
  - 0 = >=120 mg/dl
  - 1 = <120 mg/dl
- **restecg**, resting electrocardiographic results, **Category**
  - 1 = normal
  - 2 = having ST-T wave abnormality
  - 3 = showing probable or definite left ventricular hypertrophy
- **thalach**,  maximum heart rate achieved, **Float**
- **exang**, exercise induced angina, **Category**
  - 0 = no
  - 1 = yes
- **oldpeak**, ST depression induced by exercise relative to rest. **Float**
- **slope**, the slope of the peak exercise ST segment, **Category**
  - 1 = upsloping
  - 2 = flat
  - 3 = downsloping
- **ca**, number of major vessels (0-3) colored by fluoroscopy, **Float**
- **thal**, thalium heart scan, **Category**
  - 3 = normal (no cold spots)
  - 6 = fixed defect (cold spots during rest and exercise)
  - 7 = reversible defect (when cold spots only appear during exercise)
- **hd**, diagnosis of type of heart disease, the predicted attribute
 
 # Tasks
(1) Import libraries and load data <br />
(2) Exploratory Data Analysis <br />
(3) Identifying and dealing with missing value <br />
(4) Data Preprocessing <br />
(5) Understand and build a decision tree model <br />
(6) Pruning parameter - alpha <br />
(7) Data Visualization and interpretation for Decision Trees <br />

### Identifying and dealing with missing/weird data
numbers/?
- Remove the record
- impute the number with min, max or mean

