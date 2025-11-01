# Auto-Insurance-Fraud-Detection




 Project Overview

This project aims to analyze and predict fraudulent insurance claims using IBM SPSS Modeler.
The dataset insurance_claims.csv was processed, filtered, partitioned, and modeled to classify whether a claim is fraud-reported or not.



Objective

To build a data mining model that can accurately identify fraudulent auto insurance claims and help insurance companies reduce financial losses.



Steps Performed
1️ Data Import

Imported dataset: insurance_claims.csv

Contains 37 fields including customer details, incident information, and claim data.

2️ Data Preparation

Applied Filter Node to remove unnecessary or missing-value records.

Used Type Node to define measurement levels (nominal, continuous, etc.) and set the target field as fraud_reported.

3️ Data Partition

Used Partition Node to split data into:

70% Training set

30% Testing set

4️ Modeling

Applied C&R Tree (Classification & Regression Tree) to classify fraud detection.

Target Field: fraud_reported

5️ Evaluation

Generated model performance table and accuracy report.

Compared predicted vs. actual fraud cases.



<img width="1902" height="1011" alt="crtv" src="https://github.com/user-attachments/assets/6082fae3-7d7f-49e8-9141-ff3a543285f8" />


Key Outputs

Visualization of fraud vs. non-fraud claims

Decision tree showing key predictive features

Model accuracy and performance metrics




📁 Project Structure
📂 Auto_Insurance_Fraud
 ┣ 📜 insurance_claims.csv
 ┣ 📜 Auto_insurance.str  (SPSS Modeler Stream File)
 ┣ 📜 README.md
 ┗ 📸 screenshots/
     ┗ crtv.png



Conclusion

This project demonstrates the end-to-end fraud detection process using SPSS Modeler, from data import to model evaluation, providing a strong example of applied predictive analytics.



Author
Vishwajit Vishwas
Babu Banarasi Das University
Supervisor: Mr. Ayushman Bhadauria
