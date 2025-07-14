# MACHINE-LEARNING-MODEL-IMPLEMENTATION

*COMPANY*: CODETECH IT SOLUTIONS
  
*NAME*: PRATHMESH RATHOD

*INTERN ID*: CT12DK801

*DOMAIN*: Python Programming

*DURATION*: 12 WEEKS  

*MENTOR*: NEELA SANTOSH

*DESCRIPTION*: This project focuses on developing a machine learning model that can accurately predict the presence of heart disease in patients based on various medical parameters. With heart disease being one of the leading causes of death globally, early detection is critical to prevent life-threatening complications. The goal of this project is to use machine learning to assist healthcare professionals by automating part of the diagnostic process using structured data.

The dataset used in this project is a publicly available heart disease dataset, sourced from Kaggle, which itself is based on the Cleveland Heart Disease dataset from the UCI Machine Learning Repository. It contains 303 records, each representing a patient. The dataset includes 13 key features such as age, sex, chest pain type, resting blood pressure, cholesterol level, fasting blood sugar, maximum heart rate achieved, and other ECG-related variables. The target variable in the dataset indicates whether or not a patient has heart disease (1 = has disease, 0 = no disease).

The first step in the project was data preprocessing. The dataset was loaded using Pandas, and the column names were cleaned to remove unwanted whitespaces. We also renamed the condition column to target to make it consistent with machine learning conventions. An exploratory data analysis (EDA) was performed to understand correlations among features and their relationship with the target variable. Visualizations such as heatmaps and pair plots were created using Seaborn and Matplotlib to support feature selection and identify patterns in the data.

Next, the dataset was split into features (X) and labels (y). The data was divided into training and testing sets in an 80:20 ratio using train_test_split() from Scikit-learn, with stratify=y to ensure that both sets had a balanced distribution of the target classes. Since the features had different scales, StandardScaler was used to normalize the data so that each feature contributes equally to the model’s performance.

For model building, we chose Logistic Regression because it is effective for binary classification problems and offers interpretability and speed. The model was trained using the scaled training data and evaluated using the test set. The model achieved an accuracy of 91.7%, indicating high overall performance. Precision, recall, and F1-scores were calculated using classification_report(), and the confusion matrix was plotted to visualize true and false predictions.

The results showed that the model had high precision and recall, particularly for identifying patients who truly have heart disease. This is crucial in healthcare scenarios where false negatives can have serious consequences. However, some actual disease cases were missed, which suggests that improvements can be made using other algorithms like Random Forest, SVM, or ensemble methods.

In conclusion, this project successfully demonstrates how machine learning can be applied in the healthcare domain to assist in early diagnosis of heart disease. The combination of data preprocessing, logistic regression, and evaluation metrics provides a solid pipeline for binary classification tasks. This model can serve as a foundation for further enhancements and real-world applications where timely prediction is critical.

<img width="1110" height="895" alt="Image" src="https://github.com/user-attachments/assets/4efe88ca-eeeb-42df-959f-8fc171d36040" />

<img width="691" height="330" alt="Image" src="https://github.com/user-attachments/assets/50c479b7-0edf-4caa-80d9-21fa22e3257b" />

<img width="780" height="673" alt="Image" src="https://github.com/user-attachments/assets/ef472fc6-babc-423f-8ef5-06f7d3290944" />
