Machine Learning Midterm Project: Breast Cancer & Wine Datasets

This repository contains the midterm project for the Machine Learning course. The project involves a comprehensive comparative analysis of supervised (Decision Tree, KNN, Gaussian Naive Bayes) and unsupervised (K-Means) machine learning algorithms on two distinct datasets.

📌 Project Overview

The primary objectives of this project are:

Performing Exploratory Data Analysis (EDA) and data quality checks.

Preventing data leakage through strict train/validation/test splitting (3-seed repeated holdout) and isolated feature scaling.

Evaluating and comparing models using Macro-F1, Accuracy, Precision, Recall, and ROC-AUC metrics.

Selecting the best configuration based on a tie-breaker algorithm and evaluating it on an unseen test set.

Performing unsupervised K-Means clustering and comparing the Adjusted Rand Index (ARI) of scaled vs. unscaled representations.

📊 Dataset Sources

Both datasets are fetched directly from the scikit-learn library's built-in dataset module:

Breast Cancer Wisconsin (Diagnostic) Dataset: sklearn.datasets.load_breast_cancer()

Wine Classification Dataset: sklearn.datasets.load_wine()

🛠️ Python & Package Versions

Python Version: Python 3.10+ (Recommended)

Dependencies: All required packages and their exact versions can be installed via the included requirements.txt file. The main packages used are:

pandas

numpy

scikit-learn

matplotlib

seaborn

⚙️ Installation & How to Run

Follow these steps to run the project on your local machine:

Clone the repository (or extract the ZIP file):

git clone [BURAYA GITHUB REPO LİNKİNİ YAPIŞTIRIN]
cd ml-midterm


Install the required dependencies:
It is recommended to use a virtual environment. Run the following command to install the required libraries:

pip install -r requirements.txt


Run the Jupyter Notebooks:
Open the notebooks to review the code, outputs, and visualizations:

jupyter notebook


Run breast_cancer.ipynb and wine.ipynb to see the complete analysis for each dataset.

📁 Project Structure

breast_cancer.ipynb - Data analysis and modeling for the Breast Cancer dataset.

wine.ipynb - Data analysis and modeling for the Wine dataset.

report.docx - Detailed comparison report and answers to the midterm questions.

requirements.txt - Required Python packages.

classifier_runs.csv / classifier_summary.csv / classifier_test.csv - Exported results for classifiers.

kmeans_runs.csv / kmeans_summary.csv / kmeans_test.csv - Exported results for K-Means clustering.

🔗 Links

GitHub Repository: https://github.com/AbdullahEsad/Machine_Learning_Midterm

Project Presentation Video: [https://youtu.be/2DSj2LPIGTg](https://youtu.be/K-Wl9zv3hk0)    
