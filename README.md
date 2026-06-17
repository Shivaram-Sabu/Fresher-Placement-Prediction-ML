🎓 Entry-Level Tech Market Hiring Predictor

🚀 Try the Live Web Application Here![https://freshersjoblens.lovable.app]

📌 Project Overview

An end-to-end Data Science and Machine Learning pipeline that analyzes a dataset of 5,000 recent engineering graduates to predict their job hiring outcomes. This project uncovers the true impact of CGPA, internships, and project counts on securing a job offer in the Indian tech market.

📊 Key EDA Insights (The "Why")

Before building the model, I performed deep Exploratory Data Analysis (EDA) and uncovered several critical trends in the current hiring market:

The CGPA Myth: Data reveals that a high CGPA acts as a gatekeeper for resume screening, but does not guarantee the final offer. The median CGPA of rejected candidates is nearly identical to those who actually received offers.

The Great Equalizer (Projects vs. Internships): Having a prior internship drastically increases the probability of receiving an offer. However, candidates without internships can match that exact same probability by completing 4 to 5 personal projects.

Skill Diversity: The total number of technical skills listed by a candidate is a top-3 driving factor in moving past technical interviews.

🧠 Machine Learning Implementation

I engineered custom features and trained a predictive model to classify whether a candidate will receive an offer or be rejected.

Algorithm: Random Forest Classifier

Handling Imbalanced Data: Job offers are inherently rare (~12% of the dataset). I utilized class_weight='balanced' within the Random Forest architecture to heavily penalize the model for missing successful candidates.

Feature Engineering: Calculated candidate skill_count from raw text strings, filled strategic missing values (e.g., assuming 0 salary for non-offers), and utilized One-Hot Encoding for categorical roles and degrees.

💻 Tech Stack

Data Processing: Python, Pandas, NumPy

Machine Learning: Scikit-Learn (RandomForest, Confusion Matrices, Classification Reports)

Data Visualization: Matplotlib, Seaborn, Plotly

Web Frontend: React / Lovable (Live UI)

📂 Repository Structure

fresher_hiring_india_dataset.csv: The raw dataset containing 5,000 candidate profiles.

Fresher_Hiring_EDA_and_ML.ipynb: The complete Google Colab/Jupyter Notebook containing data cleaning, visualizations, and model training.
