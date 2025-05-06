# Anomaly-Detection-System
This is an anomaly detection system using machine learning algorithms .This project focuses on developing a machine-learning model for anomaly detection in health records. Traditional methods such as manual audits or rule-based systems are not enough due to the scale and complexity of healthcare data. A publicly available health records dataset from Kaggle contains 55,500 records with no missing values is used here. The steps are data collection and preprocessing, feature selection, model selection, and finally, model implementation. 
<br><br>
Algorithm Implementation – 
<br>Several machine learning models were implemented to detect anomalies .They are as follows:<br>
-Isolation Forest -	Trained on dataset by isolating anomalies by splitting the feature space. Tuned the hyperparameters number of estimators, maximum samples , and contamination rate to improve accuracy of the model.<br>
-One class SVM- Estimated anomalies based on radial basis function (RBF) kernel based on density estimation.<br>
-Local Outlier Factor(LOF)- Detected local deviation in feature density to detect anomalies. Tuning of a number of neighbors and contamination levels was done for better results. <br>
-Autoencoders- Deep learning-based approach with symmetrical neural networks that detect anomalies based on reconstruction errors.<br>

