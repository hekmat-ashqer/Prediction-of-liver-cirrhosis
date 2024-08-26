# Liver Disease Prediction Using Machine Learning
## Predicting Liver Disease Based on Biomarkers and Patient Data

**Author**: Hikmat Ashqar

## Overview of Liver Disease Prediction Project
In the realm of healthcare, early detection of liver disease can significantly improve patient outcomes and treatment efficacy. This project focuses on developing a machine learning model to predict liver disease based on patient biomarkers and demographic data. By analyzing clinical data, this model aims to assist healthcare providers in diagnosing liver disease with greater accuracy, facilitating timely intervention.

### Business Problem:
Liver diseases are often diagnosed at advanced stages due to the subtle nature of early symptoms. This project aims to predict liver disease using readily available clinical data, helping to identify at-risk patients early and improve diagnostic accuracy. The goal is to enhance healthcare providers' ability to make informed decisions and provide better patient care.

### Data:
The dataset comprises patient records, including various biomarkers and demographic information relevant to liver function and health. It includes features such as age, gender, total bilirubin, direct bilirubin, alkaline phosphatase, and other liver-related attributes.

### Data Dictionary
- **Age**: Age of the patient.
- **Gender**: Gender of the patient (Male/Female).
- **Total Bilirubin**: A measure of the total amount of bilirubin in the blood.
- **Direct Bilirubin**: A measure of the conjugated bilirubin in the blood.
- **Alkaline Phosphatase**: An enzyme related to the bile ducts; often increased when they are blocked.
- **Alamine Aminotransferase**: An enzyme found mainly in the liver; useful in diagnosing liver diseases.
- **Aspartate Aminotransferase**: An enzyme found in various parts of the body including the liver and heart.
- **Total Proteins**: Total amount of proteins in the blood.
- **Albumin**: A protein made by the liver; levels can be indicative of liver function.
- **Albumin and Globulin Ratio**: A calculated value from the levels of albumin and globulin in the blood.
- **Liver Disease**: Binary classification indicating the presence (1) or absence (0) of liver disease.

## Methods
- **Data Preparation**: Cleaned the dataset to handle missing values and outliers, and standardized the data to ensure consistency. Categorical features were encoded, and numerical features were scaled.
- **Exploratory Data Analysis (EDA)**: Performed to understand the distribution of data and identify key features influencing liver disease. Visualizations included histograms, box plots, and correlation heatmaps.

![correlations heatmap](https://github.com/user-attachments/assets/40604cb0-e8c3-47bd-8941-0ae17dcab6d4)
## Results

### Key Biomarkers Influencing Liver Disease
- **Bilirubin Levels**: Higher levels of total and direct bilirubin were strongly associated with the presence of liver disease.
- **Enzyme Activity**: Elevated levels of Alkaline Phosphatase, Alamine Aminotransferase, and Aspartate Aminotransferase were observed in patients with liver disease.

### Feature Importance Analysis
Using feature selection techniques and statistical methods, key biomarkers such as Total Bilirubin, Direct Bilirubin, and Alkaline Phosphatase were identified as significant predictors of liver disease. This allowed for the optimization of the model by focusing on the most relevant features.

## Model
### Recommended Model: Random Forest Classifier
The Random Forest classifier was selected due to its ability to handle high-dimensional data and its robustness against overfitting.

#### Model Evaluation Metrics:
- **Accuracy**: 85%
- **Precision**: 82%
- **Recall**: 87%
- **F1 Score**: 84%

### Model Performance
The Random Forest model demonstrated strong performance, accurately identifying patients with liver disease, thus serving as an effective tool for early diagnosis.

## Conclusion
The Liver Disease Prediction project successfully utilized machine learning techniques to predict liver disease based on patient biomarkers. The project demonstrated the importance of data preprocessing and feature selection in building accurate models. The insights from this project can be used to improve diagnostic procedures and support healthcare professionals in making informed decisions.

## Recommendations:
- **Integration with Clinical Systems**: Incorporate the model into clinical decision support systems to assist doctors in diagnosing liver disease early.
- **Regular Model Updates**: As new data becomes available, the model should be retrained to maintain its accuracy and reliability.
- **Further Research**: Investigate additional biomarkers and patient data to enhance model accuracy and generalizability.

## Limitations & Next Steps
- **Data Quality**: The accuracy of predictions depends on the quality and completeness of patient data. Future work should focus on collecting more comprehensive datasets.
- **Model Generalization**: Testing on broader and more diverse populations to ensure the model's applicability across different demographic groups.

### For further information
For any additional questions, please contact **[hekmat.ashqer@gmail.com]**.

