# Iris Flower Classification
Classify Iris flowers into Setosa, Versicolor, and Virginica species using classic machine learning techniques.

# Project Overview
- Dataset: The well-known Iris dataset (150 samples, 4 features: sepal/petal length and width).
- Objective: Train classification models (e.g., Decision Tree, Random Forest, Naive Bayes) to accurately predict flower species.
- Key Achievements:
  * Built and evaluated multiple models.
  * Tuned the top-performing model (Random Forest achieved ~97–98% test recall).
  * Created detailed exploratory data analysis (EDA) and feature insights.
 
# Data Exploration & Preprocessing
- Loaded the Iris dataset using Pandas.
- Explored distributions and relationships (histograms, pairplots, correlation matrices).
- Checked for nulls/outliers and handled data cleaning.
- Encoded categorical species labels and prepared feature matrices & target vectors.

# Modelling & Evaluation
- Model	Test Recall (%)	Highlights
  * Decision Tree (tuned)	~95.6%	Interpretable, easy to understand
  * Random Forest (tuned)	~97.8%	Best balance of performance & simplicity
  * Naive Bayes (tuned)	~97.8%	Simple probabilistic baseline
- Metrics used: Recall, Precision, F1 Score.
- Focus was on avoiding overfitting: best-generalizing models selected by comparing train/test performance.

# Technology Stack
- Language: Python
- Libraries: pandas, NumPy, scikit-learn, matplotlib, seaborn
- Environment: Jupyter Notebook
- Version Control: Git + GitHub

# How to Run
1. Clone the repository:
  - git clone https://github.com/swekriti12/Iris-Flower-Classifications.git
  - cd Iris-Flower-Classifications
2. Open the Jupyter Notebook (Iris Flowers Classification.ipynb) to explore end-to-end workflow.
3. Run all cells to replicate data loading, EDA, model training, evaluation, and results.

# Project Highlights
- Comprehensive EDA to understand feature importance and data patterns.
- Model comparison with metrics to select the best performing model.
- Focus on model generalization, avoiding overfitting.
- Clean, reproducible model pipeline from raw data → preprocessing → model → evaluation.
