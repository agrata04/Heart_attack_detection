# Heart_attack_detection
The projects purpose is to detect heart attack using machine learning algorithms
The goal of this project is to develop a machine learning model that can accurately classify whether a person is likely to experience a heart attack or not based on a set of clinical attributes. The dataset used for this project was collected at Zheen Hospital in Erbil, Iraq, from January 2019 to May 2019.

The dataset contains the following attributes:

Age: The age of the patient.
Gender: The gender of the patient (0 for female, 1 for male).
Heart Rate: The heart rate of the patient.
Systolic Blood Pressure: The systolic blood pressure of the patient.
Diastolic Blood Pressure: The diastolic blood pressure of the patient.
Blood Sugar: The blood sugar level of the patient (1 if > 120, otherwise 0).
CK-MB: The level of CK-MB enzyme.
Troponin: The level of troponin enzyme.
Output: The target variable indicating whether a heart attack occurred (1 for positive, 0 for negative).
The project involves the following steps:

Data Loading: The dataset is loaded into the project using the Pandas library.
Data Preprocessing: The dataset is split into features (X) and the target variable (y). The gender column is already normalized, and the glucose column is binary-encoded.
Data Split: The dataset is divided into training and testing sets using the train_test_split function from scikit-learn. The testing set constitutes 20% of the data.
Model Selection and Training: A machine learning classifier (Gradient Boosting) is chosen and instantiated. The classifier is then trained on the training set.
Prediction: The trained model is used to make predictions on the testing set.
Model Evaluation: The accuracy of the model is calculated by comparing the predicted labels with the actual labels using the accuracy_score function from scikit-learn.
The final output of this project is the accuracy of the trained model, which represents its ability to correctly classify whether a person is at risk of a heart attack based on the given clinical attributes. This project can serve as a valuable tool for healthcare professionals in the early detection and prevention of heart attacks, potentially saving lives and improving patient outcomes.





