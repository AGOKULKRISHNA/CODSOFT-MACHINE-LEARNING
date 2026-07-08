**Credit Card Fraud Detection using Machine Learning**

This project focuses on detecting fraudulent credit card transactions using supervised machine learning techniques. It implements Random Forest Classifier and Decision Tree Classifier to classify transactions as either legitimate or fraudulent based on historical transaction data.

The workflow begins by loading the training and testing datasets, followed by data preprocessing. Categorical features are encoded using LabelEncoder, and the data is prepared for model training. Both machine learning models are then trained using the processed training dataset.

After training, the models are used to predict the classes of the test dataset. Their performance is evaluated using key classification metrics such as Accuracy, Precision, Recall, and F1-Score, along with a detailed classification report.

*Model Performance*
Random Forest Classifier Accuracy: 99.76%

Decision Tree Classifier Accuracy: 99.54%

To better understand the prediction results, the project visualizes the Confusion Matrix, highlighting the number of correctly and incorrectly classified fraudulent and legitimate transactions.

Additionally, the project generates the Receiver Operating Characteristic (ROC) Curve and calculates the Area Under the Curve (AUC), providing a comprehensive measure of each model's ability to distinguish between fraudulent and genuine transactions.

Overall, this project demonstrates the practical application of machine learning in fraud detection and showcases how predictive models can help improve transaction security in real-world financial systems.
