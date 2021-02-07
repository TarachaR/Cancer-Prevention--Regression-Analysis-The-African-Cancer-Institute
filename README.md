# Cancer Prevention-Regression Analysis (The African Cancer Institute)
---

> Author: Richard Taracha

> Date: 03/02/2021

![aci](https://user-images.githubusercontent.com/67068918/107158150-3977d700-6999-11eb-9603-63f72f2741a9.png)

---

### Table of Contents
- [Background Information](#background-information)
- [Understanding The Context](#understanding-the-context)
- [Project Deliverable](#project-deliverable)
- [Recording the Experimental Design](#recording-the-experimental-design)
- [Summary Of Findings](#summary-of-findings)
- [Recommendations](#summary-of-findings)
- [Challenging your Solution](#challenging-your-solution)
- [Author Information](#author-information)

---

## Background Information
The African Cancer Institute at Stellenbosch University aims to contribute to improving cancer prevention (both primary and secondary prevention, including screening), diagnosis and management in Africa. The institute is a coordinating and directive institution for research and training in the field of cancer within the University.
</br>
</br>
Website: https://aci.org.za/

## Understanding The Context

As a Data Scientist working for the institution you have been tasked to identify factors that contribute to the death rate of cancer patients using collected dataset.
In addition, you have also been requested to build a multiple linear regression model to predict the death rate - **"TARGET_deathRate"**. You will be required to check for the assumptions of your model as well as perform k-fold (k=10) cross-validation while challenging your solution.

#### Technologies and Tools

- Python
- Pandas
- Numpy
- Matplotlib
- Scikit-Learn

[Back To The Top](#Cancer-Prevention-Regression-Analysis-The-African-Cancer-Institute)

---

## Project Deliverable
Deliverable is a Python notebook with the Ensembel Learning Techniques (Bagging and Boosting).

* Notebook name: Cancer Prediction-Regression Analysis.ipynb

**Dataset 1 name:** kopokopo_dataset - datasets_602860_1082167_SBAcase.11.13.17 
</br>
**Dataset 2 name:** kopokopo_clean.csv

</br>

**Dataset URL:** https://bit.ly/KoppoKoppoDS

**Dataset Glossary Name:** Koppokoppo - Glossary - t0001-10.1080_10691898.2018.1434342 (1).csv
</br>
**Dataset Glossary Download Link:** https://bit.ly/KoppokoppoGlossary


NB: Each row represents a customer, each column contains customer’s attributes described on the column Metadata.

[Back To The Top](#Cancer-Prevention-Regression-Analysis-(The African Cancer Institute))

---

## Recording the Experimental Design
1. Define the Research Question.
2. Data Importation.
3. Data Exploration.
4. Data Cleaning.
5. Data Analysis (Univariate & Bivariate analysis using Pandas Profling as we had a numerous number of features) </br>
**Pandas Profiling Report**: output.html
6. Data Preparation
7. Data modelling.
8. Model Evaluation.
9. Summary of Findings
10. Recommendations / Conclusions
11. Challenge solution.

[Back To The Top](#Ensemble-Learning--Kopo-Kopo-Loan-Repayment-Prediction)

---

## Summary Of Findings
* The ensemble learning classifiers and the decision tree classifier returned 100% accuracy scores with no false positives or false negatives.

[Back To The Top](#Ensemble-Learning--Kopo-Kopo-Loan-Repayment-Prediction)

---

## Recommendations / Conclusions
While these are great scores, I would recommend that the decision makers at Koppokoppo exercise caution while using these methods due to overfitting. Just because the models were perfectly accurate with this data does not mean the same will happen with different data.

[Back To The Top](#Ensemble-Learning--Kopo-Kopo-Loan-Repayment-Prediction)

---

## Challenging your Solution
* Meeting the assumptions of the algorithms (e.g., no multicollinearity, normality, etc. for logistic regression)

* Performing hyperparameter tuning.

* Feature selection - discarding the features considered unnecessary or unimportant.

* Cross Validation

[Back To The Top](#Ensemble-Learning--Kopo-Kopo-Loan-Repayment-Prediction)

---

## Author Information

- Twitter - https://twitter.com/Vycellous_Drum
- Website - https://richardtaracha.glitch.me/

[Back To The Top](#Ensemble-Learning--Kopo-Kopo-Loan-Repayment-Prediction)
