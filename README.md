# Heart Failure Prediction Data Analysis  
The dataset for this project is from Kaggle
> [Kaggle dataset](https://www.kaggle.com/datasets/fedesoriano/heart-failure-prediction)  

## Notebook Content:

- **Step 1**: Install and import necessary libraries
- **Step 2**: Reading and exploring data
- **Step 3**: Data cleaning and preprocessing
- **Step 4**: Descriptive Statistics
- **Step 5**: Data Analysis and visualization
- **Step 6**: Predictive models  

### Libraries needed:
- pandas
- matplotlib
- seaborn
- plotly.express and plotly.graph_objects
- numpy
- scipy.stats
- sklearn - linear regression, logistic regression, train_test_split, Decision tree classfier.  

### Reading and exploring data  

First we will read the csv file downloaded from Kaggle and read it into jupyter notebook using `pd.read_csv`  
The attributes of the data set are as follows:  
- Age: age of the patient [years]
- Sex: sex of the patient [M: Male, F: Female]
- ChestPainType: chest pain type [TA: Typical Angina, ATA: Atypical Angina, NAP: Non-Anginal Pain, ASY: Asymptomatic]
- RestingBP: resting blood pressure [mm Hg]
- Cholesterol: serum cholesterol [mm/dl]
- FastingBS: fasting blood sugar [1: if FastingBS > 120 mg/dl, 0: otherwise]
- RestingECG: resting electrocardiogram results [Normal: Normal, ST: having ST-T wave abnormality (T wave inversions and/or ST elevation or depression of > 0.05 mV), LVH: showing probable or definite left ventricular hypertrophy by Estes' criteria]
- MaxHR: maximum heart rate achieved [Numeric value between 60 and 202]
- ExerciseAngina: exercise-induced angina [Y: Yes, N: No]
- Oldpeak: oldpeak = ST [Numeric value measured in depression]
- ST_Slope: the slope of the peak exercise ST segment [Up: upsloping, Flat: flat, Down: downsloping]
- HeartDisease: output class [1: heart disease, 0: Normal]