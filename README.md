# Patient Readmissions Prediction

Welcome to the Patient Readmissions Prediction project! This project was developed as part of the Machine Learning course for the 2023/2024 academic year. Our objective is to use various machine learning models, from single algorithms to ensemble techniques, to predict whether a patient will be readmitted in the hospital or not.

## Table of Contents
- [Project Overview](#project-overview)
- [Data](#data)
- [Methodology](#methodology)
- [Results](#results)
- [How to Run](#how-to-run)

## Project Overview
Hospital readmissions represent a significant challenge in the healthcare sector, both as an indicator of care quality and a driver of escalating costs. When a patient is re-admitted to the hospital within a short period after discharge, it not only indicates potential gaps in care but also adds to the financial burden on the healthcare system. In particular, readmissions of diabetic patients have been noted to contribute significantly to these costs. Therefore, being able to predict such readmissions can lead to improved patient care and substantial cost savings.

The goal of this project is two-fold:
- Binary Classification: Create a classification model that can accurately predict if a patient will be readmitted to the hospital within 30 days of
being discharged. A robust prediction can enable healthcare providers to implement preventive measures and provide timely intervention, potentially saving millions of dollars in healthcare costs.
- Multiclass Classification: The second objective is to develop a multiclass classifier that predicts the timeframe of a patient’s readmission, with the classes being “No”, “<30 days”, “>30 days”. This model can provide more nuanced insights into patient risk levels and help hospitals tailor their post-discharge care and follow-up procedures accordingly.

## Data
The data used for this project is provided in the following files, in the Data folder:
- `train.xlsx`: Contains the various features and target variables for the project.
- `test.xlsx`: Contains the structure of the test set, which matches the training set but without the target labels.

## Methodology
1. **Data Preprocessing**: Cleaning and preparing the data for analysis.
2. **Feature Engineering**: Extracting relevant features from the data.
3. **Model Training**: Training ML models using libraries such as Scikit-Learn.
4. **Evaluation**: Assessing the model's performance using appropriate metrics.

## Results
The final model's performance and key findings are detailed in the `Machine_Learning_Report`.

## How to Run
To run the project, follow these steps:

1. Clone the repository:
    ```bash
    git clone https://github.com/ShinoNice/Patient-Readmissions
    cd Patient-Readmissions

For any questions or further information, feel free to contact me via GitHub.

Happy coding!
