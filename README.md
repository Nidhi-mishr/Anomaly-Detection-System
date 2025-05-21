# Anomaly-Detection-System
This is an anomaly detection system using machine learning algorithms .This project focuses on developing a machine-learning model for anomaly detection in health records. Traditional methods such as manual audits or rule-based systems are not enough due to the scale and complexity of healthcare data. A publicly available health records dataset from Kaggle contains 55,500 records with no missing values is used here. The steps are data collection and preprocessing, feature selection, model selection, and finally, model implementation. 
<br><br>
Algorithm Implementation – 
<br>Several machine learning models were implemented to detect anomalies .They are as follows:<br>
-Isolation Forest -	Trained on dataset by isolating anomalies by splitting the feature space. Tuned the hyperparameters number of estimators, maximum samples , and contamination rate to improve accuracy of the model.<br>
-One class SVM- Estimated anomalies based on radial basis function (RBF) kernel based on density estimation.<br>
-Local Outlier Factor(LOF)- Detected local deviation in feature density to detect anomalies. Tuning of a number of neighbors and contamination levels was done for better results. <br>
-Autoencoders- Deep learning-based approach with symmetrical neural networks that detect anomalies based on reconstruction errors.<br>
<br>
The result obtained from machine learning models is as follows:<br>
The isolation forest model was rigorously optimized through hyperparameter tuning, including the number of estimators, contamination factor, and maximum samples. This resulted in a solid accuracy of 90%.<br>
The one-class Support Vector Machine (SVM) achieved an impressive accuracy of 92% by precisely tuning hyperparameters nu and gamma, which govern the trade-off between margin maximization and classification errors.<br>
The local outlier factor model demonstrated strong performance by adjusting the number of neighbors and contamination levels, achieving an accuracy of 91.4%.<br>
Lastly, the autoencoder, designed for unsupervised learning via reconstruction errors, was finely tuned to achieve an outstanding accuracy of 92.1%. This model effectively identifies anomalies by capturing the essential features of the data through its reconstruction abilities!<br><br>

Future work that can be done is as follows: -<br>
-Exploring advanced deep learning architectures <br>
-Addressing data quality issues <br>
-Develop a real-time anomaly detection system <br>



