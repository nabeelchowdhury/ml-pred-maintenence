Predictive Maintenance Model Using Machine Learning
This project demonstrates the application of supervised learning to predict the failure status of machines using variables such as temperature, vibration level, and operational hours. By training a Random Forest classifier, we aim to identify potential failures before they occur, allowing for timely maintenance and reducing downtime.

Implementation Details
Data Preparation
We start by augmenting our dataset with additional sensor data, which includes measurements of temperature, vibration level, and operational hours, along with the failure status of the machinery. This data is then concatenated with the original dataset to provide a comprehensive view of the machine's condition over time.

Feature Selection and Model Training
The dataset is split into features (X) representing the machine conditions, and a target variable (y) indicating the failure status. We utilize a Random Forest classifier due to its robustness and ability to handle non-linear data. The classifier is trained on this combined dataset to predict the failure status of the machines.

Model Evaluation
To assess the performance of our predictive maintenance model, we employ evaluation metrics such as accuracy, classification reports, and confusion matrices. These metrics provide insight into the model's effectiveness in predicting machine failures and help identify areas for improvement.
