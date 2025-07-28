Donor Income Prediction

Predicting whether individuals earn more than $50,000 based on census data using supervised machine learning models.
This project is part of the Udacity Machine Learning Engineer Nanodegree.
📌 Project Overview

The goal of this project is to build a model that can predict whether a person earns more than $50,000 annually based on census data.
We use multiple supervised learning algorithms, optimize their performance, and evaluate them using metrics such as F1-score and accuracy.
🛠️ Features

    Data preprocessing and cleaning of census data

    Feature engineering (encoding categorical variables, scaling numerical features)

    Implementation and comparison of multiple supervised learning algorithms:

        Decision Trees

        Random Forests

        Support Vector Machines (SVM)

        AdaBoost

    Model evaluation with cross-validation

    Hyperparameter tuning using GridSearchCV

📂 Project Structure

├── finding_donors.ipynb     # Main Jupyter Notebook with code and analysis
├── README.md                # Project documentation
├── .gitignore               # Ignored files/folders (optional)
└── requirements.txt         # Python dependencies (optional)

🚀 Getting Started
1. Clone the Repository

git clone https://github.com/yourusername/donor-income-prediction.git
cd donor-income-prediction

2. Install Dependencies

Make sure you have Python 3.8+ installed. Install required packages:

pip install -r requirements.txt

3. Run the Notebook

Launch Jupyter Notebook:

jupyter notebook finding_donors.ipynb

📊 Dataset

The dataset used in this project is the U.S. Census Adult Income dataset (also known as the "Adult" dataset).

    Source: UCI Machine Learning Repository

    Target: Income level (<=50K or >50K)

📈 Model Performance

    Best Model: AdaBoost Classifier

    F1 Score (Optimized): ~0.76

    Accuracy: ~87%
