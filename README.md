# 🧪 Hepatitis C diagnosis using machine learning

This repository contains my Master's Thesis (TFM) in Biostatistics and Bioinformatics, focused on building and comparing machine learning models to predict hepatitis C based on clinical and biochemical data.

## 🎯 Objective

To develop and evaluate predictive models for hepatitis C diagnosis using supervised machine learning techniques, including data exploration, hypothesis testing, feature correlations, and model performance analysis.

## 📁 Project structure
hepatitisC-TFM/
│
├── data/
│ └── hepatitisC.csv # Original dataset
│
├── notebooks/
│ ├── 01_EDA.ipynb # Exploratory data analysis
│ ├── 02_Statistics.ipynb # Hypothesis tests and correlations
│ ├── 03_Modeling.ipynb # Model training and evaluation
│ └── 04_Report_Generation.ipynb # Tables and figures for the final report
│
├── utils/
│ └── data_utils.py # Clean reusable functions
│
├── figures/
│ └── *.png # Exported visualizations
│
├── README.md
├── RUN.md # Instructions to run this project
└── requirements.txt

## 🛠️ Tools and libraries

- Python 3.10+
- Pandas, NumPy, SciPy, Statsmodels
- Matplotlib, Seaborn
- Scikit-learn, XGBoost
- Power BI / Tableau (optional for dashboard visualizations)
- Jupyter Notebook

## 🧪 Analysis overview

- Data cleaning and preprocessing
- Variable distributions and exploratory plots
- Hypothesis testing (t-test, chi²)
- Correlation analysis (Pearson, Spearman)
- Machine learning models: logistic regression, random forest, SVM, KNN, XGBoost
- Performance comparison: accuracy, recall, F1-score, ROC-AUC
- Result interpretation and visual summary

## 📊 Dataset

The dataset `hepatitisC.csv` includes:
- Patient age and sex
- Several biochemical markers (ALB, ALP, ALT, AST, etc.)
- Diagnostic category for hepatitis C

## 🚀 How to run the project

Please refer to the [RUN.md](./RUN.md) file for detailed instructions on setting up the environment and running the notebooks step by step.

## 👩‍⚕️ Author

**Elena Álvarez**  
Master's in Biostatistics and Bioinformatics – CEMP  
[LinkedIn](https://www.linkedin.com/in/elenaalvg)

## 📄 License

This project is for academic and educational purposes only. It should not be used for real-world clinical decision-making without expert validation.
