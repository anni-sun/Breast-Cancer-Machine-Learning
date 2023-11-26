**Breast Cancer Prediction Machine Learning**

The problem we are going to solve using this dataset is Breast Cancer Prediction. We are going to build prediction models based on the predictors in the dataset as biomarkers of breast cancer to predict if the person is a patient or is healthy control.
The quantitative attributes related to breast cancer are Age (years), BMI (kg/m2), Glucose (mg/dL), Insulin (µU/mL), HOMA (Homeostatic Model Assessment), Leptin (ng/mL), Adiponectin (µg/mL), Resistin (ng/mL), MCP-1(Monocyte chemoattractant protein-1; pg/dL).
We pre-process the dataset by dropping three columns that have the lowest correlations with the output class to ensure performances of our models.
The prediction models we decide to build and tune are Logistic Regression, Linear SVM, Decision Tree and Random Forests. We decide to build these models since they are supervised learning models and are the most efficient models for prediction.
