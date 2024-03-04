# Seismic-Activity-in-Poland
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1BHxLpRvc7pFDeyI9j_Cnv6KeL_OdgiNp?usp=sharing)

# Report on Seismic Bumps Dataset Analysis
This report provides an overview of a study conducted on seismic hazard prediction using machine learning techniques. The dataset utilized is sourced from the UCI Machine Learning Repository and consists of records from the Zabrze-Bielszowice coal mine in Poland. The primary objective is to predict hazardous seismic events based on various attributes recorded during work shifts.

| Epicenter of the Earthquakes                                |
|-------------------------------------------------------------|
| ![poland 640](https://github.com/Oaky112/Seismic-Activity-in-Poland-/assets/88333204/ed1c873f-a5b4-4911-821e-48ab787f90c4) |


## Key Points:

Dataset Description: The dataset comprises categorical and numeric variables, including seismic readings, energy levels, and bump counts. A 'hazardous bump' is defined as having seismic energy exceeding 10,000 Joules.

Data Handling: Initial steps involve checking for missing values and removing redundant features. The class distribution imbalance necessitates sampling methods for model training.

Model Training: Logistic regression, Random Forest, and Decision Tree techniques are employed for seismic hazard prediction. The logistic regression model achieved 91.3% accuracy on test data.

Data Pre-processing: Pre-processing steps include normalization and feature selection. Visualization aids in understanding class distributions and correlations between variables.

Model Evaluation: Model performance is assessed using metrics like accuracy, precision, recall, and F1-score, along with confusion matrices. The logistic regression model provided insights into correct and incorrect predictions.

![image](https://github.com/Oaky112/Seismic-Activity-in-Poland-/assets/88333204/1def97aa-6f7b-4e1a-9779-0d5ccfc5a7c1)


Conclusion:
This study demonstrates the application of machine learning techniques for seismic hazard prediction. While the logistic regression model yielded promising results, future work may explore advanced modeling techniques and real-time data integration for more accurate predictions.
