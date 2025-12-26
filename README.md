# Project Overview
This project focuses on building a machine learning–based system to predict whether a breast tumor is malignant or benign using medical diagnostic data. The project demonstrates the complete ML pipeline — from data preprocessing to model evaluation — and highlights practical applications of data science in healthcare.

 Project Structure
Breast-Cancer-Prediction/
│
├── Breast_cancer_dataset_1.ipynb   # Data loading and exploration
├── Breast_cancer_dataset_2.ipynb   # Data preprocessing & feature handling
├── Breast_cancer_dataset_3.ipynb   # Model training and evaluation
└── README.md

# Dataset Overview
The dataset consists of various numerical features computed from digitized images of breast mass samples.
Key Features Include:
Radius
Texture
Perimeter
Area
Smoothness
Compactness
Concavity
Symmetry

# Target Variable:
Diagnosis → Benign (0) or Malignant (1)

# Tools & Technologies Used
Python
Pandas – data manipulation
NumPy – numerical operations
Scikit-learn – machine learning & evaluation
Matplotlib / Seaborn – visualization
Jupyter Notebook

# Project Workflow
1️ Data Exploration
Loaded dataset and inspected structure
Checked for missing values and inconsistencies
Analyzed feature distributions

2️ Data Preprocessing
Converted categorical labels into numerical format
Split dataset into training and testing sets
Applied feature scaling where required

3️ Model Development
Trained machine learning classification models
Evaluated model performance using accuracy and classification metrics

4️ Model Evaluation
Compared predicted vs actual outputs
Assessed reliability and model effectiveness

# Key Learnings
Clean and structured data significantly improves model performance
Feature selection plays a crucial role in prediction accuracy
Machine learning can assist in early medical diagnosis when used responsibly

# How to Run the Project
Clone the repository:
git clone https://github.com/ananyansinha/breast-cancer-prediction.git
Install required libraries:
pip install pandas numpy scikit-learn matplotlib seaborn
Open the notebooks in Jupyter Notebook or Google Colab
Run the cells sequentially

# Future Enhancements
Implement advanced models (Random Forest, XGBoost)
Add hyperparameter tuning
Deploy the model using Streamlit
Integrate explainable AI techniques (SHAP / LIME)

# Author
Ananya Sinha
B.Tech Computer Science
Aspiring Data Analyst | Business & Analytics Enthusiast
