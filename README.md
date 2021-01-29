# FraudDetection_DL_W5
In this task, the goal is to detect fraudulent credit/debit card transactions (anomaly detection). First, we train autoencoder to reproduce the feature vector of normal transactions. Then, we predict the train set features (including both normal and fraudulent transactions). Finally, we check if the distance between original features and reproduced ones is larger than a threshold we assume it is fraudulent and if not it is a normal transaction. We use Keras for autoencoder development.
The dataset is available in
https://www.kaggle.com/mlg-ulb/creditcardfraud
