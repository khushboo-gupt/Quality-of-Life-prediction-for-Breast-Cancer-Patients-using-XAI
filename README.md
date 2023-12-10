# Quality-of-Life-prediction-for-Breast-Cancer-Patients-using-XAI

# Overview
This repository contains code and documentation for the "Life Prediction for Breast Cancer Patients" project. The project focuses on predicting the life expectancy and survival rates of individuals diagnosed with breast cancer using machine learning techniques, with an emphasis on Explainable AI (XAI). The SHAP (SHapley Additive exPlanations) library is utilized for model interpretability.

# Dataset
We utilize the Molecular Taxonomy of Breast Cancer International Consortium (METABRIC) dataset, a valuable resource in breast cancer research. The dataset includes clinical attributes such as patient ID, age at diagnosis, type of breast surgery, cancer type, and various other features. The dataset can be accessed here.

# Methodology
1. Dataset Overview
We provide a detailed explanation of the METABRIC dataset, including clinical attributes, cancer types, and patient information.

2. Block Diagram
We present a block diagram illustrating the key steps in the project, including dataset preparation, preprocessing, machine learning model selection (neural network), and model explainability using SHAP.

4. Flow Chart
The flow chart outlines the steps involved in the project, from data collection and preprocessing to model training, evaluation, and deployment. SHAP is integrated into the model interpretation process.

5. UML Diagrams
We include UML diagrams, including activity, sequence, and use case diagrams, to visualize the system's structure and behavior.

6. Performance Parameters
We define performance parameters and provide formulas for metrics such as accuracy, precision, recall, F1 score, area under the ROC curve, and confusion matrix.

Explainable AI with SHAP
The SHAP library is employed for model interpretability. SHAP values help in understanding the impact of each feature on model predictions, providing insights into the decision-making process.

Performance Analysis
We present the results of the project using various machine learning algorithms, including Random Forest Classifier, Random Survival Forest, Just Neural Network, Coherent Voting Network, and Extreme Gradient Boosting (XGBoost). Comparative analysis and graphs are included to evaluate and visualize the models' performance.

# Conclusion
The project concludes with a summary of findings, advantages, applicability, and future scope. The documentation emphasizes the importance of Explainable AI with SHAP in clinical decision support, patient education, research, healthcare policy, and pharmaceutical development.
In this project we trying to predict the quality of life for breast cancer patients using Explainable AI (library SHAP). We implemented 5 model random forest classifier, random survival forest, Xgboost, Coherent neural network, Just neural network. After implementing all five we get highest accuracy of 97% (random forest classifier).

# How to Use
Clone the repository: git clone https://github.com/khushboo-gupt/Quality-of-Life-prediction-for-Breast-Cancer-Patients-using-XAI.git
Install dependencies: pip install -r requirements.txt
Follow the instructions in the Jupyter notebooks for data preprocessing, model training, and evaluation.
Feel free to explore the code and documentation to gain insights into the project and contribute to its development. If you encounter any issues or have suggestions, please create an issue in the repository.

# Google Form for Data Collection

To facilitate the implementation of our model, we have created a Google Form for collecting patient information and predicting their survival status. Please use the following link to access the form:

[Google Form Link](https://docs.google.com/forms/d/1CVI0h4AJmXWt0uFGwFJg3J28GPqI-QE39HSisPyiOG0/edit)

Feel free to submit relevant data through the form, and our model will provide predictions based on the input information.

Your participation in providing data through the form is greatly appreciated as it contributes to the improvement and refinement of our breast cancer prediction model.

Thank you for your collaboration!


# Contributors
Your Name (@khushboo-gupt)
Thank you for your interest and contributions to the "Life Prediction for Breast Cancer Patients" project!
