# Cervical-Cancer-Risk-Prediction-Using-Machine-Learning

![hologram-female-organ-uterus-tablet-ultrasound-concept-gynecology-obstetrics-pregnancy-modern-medicine_99433-5827 copy](https://github.com/shirinshaik/Cervical-Cancer-Risk-Prediction-Using-Machine-Learning/assets/113626760/48b1c234-c79c-4536-aea9-e95fedb05107)


Image Source: https://www.freepik.com/premium-photo/hologram-female-organ-uterus-tablet-ultrasound-concept-gynecology-obstetrics-pregnancy-modern medicine_15342465.htm#query=cervical%20cancer%20prediction&position=39&from_view=search&track=ais

Dataset Source: https://www.kaggle.com/datasets/loveall/cervical-cancer-risk-classification

# OBJECTIVE
This project aims to develop a predictive model for assessing the risk of cervical cancer based on demographic information, sexual behavior, medical history, and diagnostic outcomes. The goal is to build a machine learning model that can predict the likelihood of an individual developing cervical cancer using these factors.

# INTRODUCTION
In this hands-on project, we embark on a journey to construct and train an XGBoost model with the purpose of predicting cervical cancer in a cohort of 858 patients. The dataset, meticulously curated at the 'Hospital Universitario de Caracas' in Caracas, Venezuela, encapsulates a rich trove of demographic information, behavioral habits, and historical medical records for each of these individuals.

Cervical cancer, a global health concern claiming the lives of approximately 300,000 women worldwide, underscores the urgency of continued research and proactive healthcare measures. Encouragingly, due to advances in medical screening, the cervical cancer mortality rate has witnessed a commendable 74% reduction from 1955 to 1992.

A pivotal revelation in cervical cancer studies has been the identification of High sexual activity Human papilloma virus (HPV) as a primary contributing factor. This insidious virus significantly heightens the risk of cervical cancer. Additionally, certain lifestyle choices such as the use of oral contraceptives, multiparity, and smoking amplify the susceptibility, particularly among women harboring HPV. Notably, individuals with weakened immune systems, often associated with conditions like HIV/AIDS, face an elevated risk of HPV infection.

Input Features:
- AGE
- NUM OF PREGNANCIES
- SMOKES
- JUD
- STDs VES

Target Variable:
- BIOPSY

The linchpin of our endeavor lies in the application of an XGBoost model, a robust machine learning algorithm known for its adeptness in classification tasks. Through rigorous training and validation, we aim to create a predictive tool that can discern the likelihood of cervical cancer development in these individuals.

# FEATURES
1. Understand the theory and intuition behind XGBoost.
2. Import Key python libraries, dataset and perform data visualization.
3. Perform exploratory data analysis and standardize the training and testing data.
4. Train and Evaluate XGBoost using Sciki-Learn Library.
5. Assess the performance of classifier models using various KPIs.
6. Split and Standardize training and testing datasets.

# TECHNOLOGIES USED
- Python
- XGBoost
- Scikit-Learn
- Data Visualization Libraries (Matplotlib, Seaborn)
- Jupyter Notebooks
- Pandas and NumPy
- Data Standardization Techniques (Feature Scaling)
- Exploratory Data Analysis (EDA) Techniques (summary statistics, histograms, scatter plots, etc)

These technologies collectively form the technical stack for this project, enabling tasks like data manipulation, model training, evaluation, and visualization.

# USAGE
The project is divided into several tasks, each contributing to the overall learning experience:

## Task #1: Understand the Problem Statement and Business Case
This task provides an overview of the problem statement, outlining the significance of predicting cervical cancer risk and its impact on public health.

## Task #2: Import Libraries and Datasets
Here, we'll learn how to set up our Python environment by importing essential libraries and loading the dataset containing demographic information, habits, and medical records of 858 patients.

## Task #3: Perform Exploratory Data Analysis
In this task, we'll dive into the dataset to gain insights through exploratory data analysis. This involves summarizing statistics, identifying patterns, and understanding the distribution of features.

## Task #4: Perform Data Visualization
Visualizing data is a crucial step in understanding relationships and trends. This task will guide us through creating visual representations of the dataset using libraries like Matplotlib and Seaborn.

## Task #5: Prepare the Data Before Model Training
Before training the model, it's important to preprocess the data. This task covers techniques such as standardization to ensure that the data is ready for the modeling phase.

## Task #6: Understand the Theory and Intuition Behind XGBoost:
This task provides a comprehensive understanding of the XGBoost algorithm, including its theoretical foundations and practical applications in machine learning.

## Task #7: Train and Evaluate XGBoost Algorithm
In this final task, we'll apply the knowledge gained to train an XGBoost model. The model will be evaluated using various performance metrics to assess its accuracy and effectiveness in predicting cervical cancer risk.

Each task is designed to build on the knowledge gained from the previous one, culminating in the successful implementation of the XGBoost algorithm for cervical cancer risk prediction.

# NOTABLE INSIGHTS
1. Key Predictive Features:
Features such as "AGE", "NUM OF PREGNANCIES", and "SMOKES" emerged as significant predictors of cervical cancer risk.

2. Model Performance:
The XGBoost model achieved an impressive accuracy of approximately 97%, indicating its effectiveness in predicting cervical cancer risk.

3. Feature Importance:
Age was identified as the most influential feature in risk assessment, underscoring its critical role in predicting cervical cancer.

4. Potential Impact:
The model's high accuracy and robust performance suggest its potential for early detection and personalized healthcare strategies.

5. Limitations:
While the model demonstrated strong performance, it's important to note that no model is perfect. There were some instances of misclassification, particularly in cases of patients with weak immune systems.

# CONCLUSION
In this hands-on project, we successfully built and trained an XGBoost model to predict cervical cancer risk in a dataset comprising 858 patients. Leveraging demographic information, habits, and medical records, the model demonstrated a remarkable accuracy of 97%. This high accuracy underscores the potential impact of machine learning in early detection and personalized healthcare.

The project not only showcased the power of XGBoost in predictive modeling but also highlighted the critical role of features like "AGE," "NUM OF PREGNANCIES," and "SMOKES" in assessing cervical cancer risk. Age, in particular, emerged as the most influential factor, reaffirming existing medical knowledge.

While the model exhibited exceptional performance, it's important to acknowledge its limitations. As with any predictive model, there may be cases of misclassification, especially among patients with weakened immune systems.

Overall, this project lays a foundation for further research and application of machine learning in the field of oncology. The insights gained here have the potential to contribute significantly to early detection efforts and personalized treatment strategies for cervical cancer.

# FUTURE WORK
Moving forward, there are two key areas that warrant further exploration. Firstly, delving deeper into feature engineering techniques could unveil additional predictive variables or interactions that contribute to the model's accuracy. This could involve a more extensive analysis of the existing features and the potential inclusion of domain-specific variables.

Secondly, fine-tuning the model's hyperparameters and conducting a more exhaustive search for optimal settings may lead to even better performance. This could involve leveraging techniques like grid search or Bayesian optimization to identify the most effective configuration for the XGBoost algorithm.

These avenues hold the potential to refine the model's accuracy and expand its applicability in real-world scenarios.

★ Cervical cancer disproportionately affects women, particularly in low-resource settings. Predictive models can provide a powerful tool for empowering women to take charge of their health through regular screenings and lifestyle adjustments

★ Accurate prediction of cervical cancer risk has a profound impact on individual lives, healthcare systems, and public health outcomes. It's a crucial step towards a healthier and more empowered society.
