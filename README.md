# Biosensing-Machine-learning-Model.ipynb
Multi-omics Biosensor Data Analysis using Python and Machine Learning to identify gene, protein, and metabolite features associated with target analyte concentration. The 15 electrochemical biosensor features describe biosensor responses. The molecular component allows integrated analysis of same biological samples across different molecular levels

Project Objective:
The objective of this project is to analyze biosensor data using Python and machine learning to identify gene, protein, and metabolite features associated with target analyte concentration. The study combines exploratory data analysis, statistical correlation, and predictive modeling to investigate relationships between molecular features and the target analyte.
The project aims to identify promising candidate features that may contribute to understanding and predicting biosensor responses.

Dataset Description:
The dataset contains biosensor-related measurements and molecular features, including genes, proteins, and metabolites.
Gene features: Gene_01 to Gene_20
Protein features: Protein_01 to Protein_20
Metabolite features: Metabolite_01 to Metabolite_20
Target variable: Target_Analyte_Concentration_ng_mL
Additional variable: Analyte_Class, representing categories of target analyte concentration.
The dataset was analyzed to explore associations between molecular features and target analyte concentration.

Exploratory Data Analysis and Statistical Analysis

Python was used to perform data cleaning, exploratory data analysis (EDA), visualization, and statistical analysis.
The workflow included:
Inspecting dataset structure, data types, and missing values.
Exploring target analyte concentration and Molecular Features
Visualizing relationships between molecular features and target concentration.
Calculating Spearman correlation coefficients to identify potential associations.
Applying false discovery rate (FDR) correction to account for multiple statistical tests.
The resultant predominant candidate genes, proteins, and metabolites were used for further investigation.
Libraries included pandas, NumPy, Matplotlib, Seaborn, SciPy, and Statsmodels, where applicable.

Machine Learning and Model Evaluation
A Random Forest Regression model was used to investigate whether molecular features could predict target analyte concentration.
The reported model evaluation results were:
R² score: 0.522
Mean Absolute Error (MAE): 1.993
Root Mean Squared Error (RMSE): 2.932
Feature importance analysis highlighted the following candidates:
Gene 14, Protein 19 and 20, Metabolites 14, 18 and 20.

Conclusion
This project demonstrates the application of Python-based data analysis, statistical correlation, and machine learning to biosensor data containing gene, protein, and metabolite features. The analysis identified Gene 14, Protein 19 and Protein 20, Metabolite 14, Metabolite 18 and Metabolite as candidate features based on the reported correlation and Random Forest feature importance results. These steps would help determine whether the observed associations are reproducible and scientifically meaningful.

