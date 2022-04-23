# SC1015 Data Science & Artificial Intelligence Project On Predicting In-Hospital Mortality
![image](http://url/to/img.png)https://github.com/pamelalee26/In-Hospital-Mortality/blob/main/Image.jpg
# Problem Definition
Our team aims to investigate how hospitals can predict the survival outcome of their in-hospital patients.  

## [Dataset](https://www.kaggle.com/datasets/saurabhshahane/in-hospital-mortality-prediction)
The dataset that we have settled on is sourced from Kaggle and is called “In Hospital Mortality Prediction”, which outlines variables including demographic characteristics such as the age of the patient, gender. BMI etc. 

## Contents In Folder
1. [Slides](https://github.com/pamelalee26/In-Hospital-Mortality/blob/main/Slides.pptx)
2. [Notebook](https://github.com/pamelalee26/In-Hospital-Mortality/blob/main/Hospital%20Mortality%20Prediction%20Final.ipynb)
3. [Transcript](https://github.com/pamelalee26/In-Hospital-Mortality/blob/main/Transcript.docx)

# Summary of Project
## Data Cleaning 
- Dealing with null values
- Feature Selection using low variance filter and pairwise correlation

## Exploratory Data Analysis
- For creatine kinase, despite the presence of extreme outliers, we decided to keep them as high levels of creatine kinase is known to be dangerous and will affect the outcome
- We also inferred that EF does not seem to have a significant impact on outcome, and thus we dropped that variable.

## Models Used
- K-Nearest Neighbours
- Logistic Regression
- Decision Tree

## Conclusion
- Number of in-hospital patients increases with age. Therefore, hospitals should pay especially careful attention to older patients as they are at higher risk of mortality. 
- Similarly, heart rate, systolic blood pressure, SPO2, Urine output etc. are notable determinants that can affect mortality outcomes.
- Hospitals should install more medical devices to monitor changes in patients’ medical statistics in these areas. 
- Hospitals can consider the use of the Random Forest machine learning algorithm to process collected data to predict the probable mortality outcome for patients. 

## Learning Outcomes
- Feature Selection
- K-Nearest Neighbours
- Logistic Regression
- Random Forest
