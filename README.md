# SC1015 Data Science & Artificial Intelligence Project On Predicting In-Hospital Mortality
![image](https://github.com/pamelalee26/In-Hospital-Mortality/blob/main/Image.jpg)
# Problem Definition
Our team aims to investigate how hospitals can predict the survival outcome of their in-hospital patients.  

## [Dataset](https://www.kaggle.com/datasets/saurabhshahane/in-hospital-mortality-prediction)
The dataset that we have settled on is sourced from Kaggle and is called “In Hospital Mortality Prediction”, which outlines variables including demographic characteristics such as the age of the patient, gender. BMI etc. 

## Contents In Folder
1. [Slides](https://github.com/pamelalee26/In-Hospital-Mortality/blob/main/Slides.pptx)
2. [Notebook](https://github.com/pamelalee26/In-Hospital-Mortality/blob/main/Notebook.ipynb)
3. [Transcript](https://github.com/pamelalee26/In-Hospital-Mortality/blob/main/Transcript.docx)
### [Our Project Presentation Video](https://www.youtube.com/watch?v=gRhFa5yBMR4)
# Summary of Project
## Data Cleaning 
- Dealing with null values
- Feature Selection using low variance filter and pairwise correlation

## Exploratory Data Analysis
- For creatine kinase, despite the presence of extreme outliers, we decided to keep them as high levels of creatine kinase is known to be dangerous and will affect 'outcome'
- We also inferred that EF does not seem to have a significant impact on 'outcome', and thus we dropped that variable.

## Models Used
- K-Nearest Neighbours
- Logistic Regression
- Random Forest

## Conclusion
- Number of in-hospital patients increases with age. Therefore, hospitals should pay especially careful attention to older patients as they are at higher risk of mortality. 
- Similarly, heart rate, systolic blood pressure, SPO2, Urine output etc. are notable determinants that can affect mortality outcomes.
- Hospitals should install more medical devices to monitor changes in patients’ medical statistics in these areas. 
- Of the 3 machine learning models used, Random Forest has the highest F1 score and accuracy, and thus it is the most ideal method of the 3.
- The low F1 scores can be attributed to the skew in 'outcome'. In order to overcome this, we can oversample the minority class or undersample the majority class.
- However, the skewed 'outcome' values models real life scenarios, as intensive care units (ICU) have an average mortality rate reported ranging from 8-19%. Thus, we have decided against oversampling or undersampling to best model reality and develop a practical and efficient predictor to help hospitals increase patient survival rates.
- Overall, we believe that hospitals can consider the use of the Random Forest machine learning algorithm to process collected data to predict the probable mortality outcome for patients and can help hospitals predict the survival rates of patients & best allocate medical resources to give patients care/support.

## Learning Outcomes
- Feature Selection
- K-Nearest Neighbours
- Logistic Regression
- Random Forest
- Log Loss Function
