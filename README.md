# AI Adoption Journey in Software Development (2022–2025)
📌 Overview

This project analyzes how software developers have adopted, perceived, and adapted to AI tools over time, using data from the Stack Overflow Developer Surveys (2022–2025).

The goal is to move beyond hype and fear, and understand real developer behavior — how AI usage evolved, what developers use AI for, how they feel about it, and whether AI adoption can be predicted using machine learning.

🎯 Objectives

This study aims to:

Track AI adoption trends among developers from 2022 to 2025
Identify which developer profiles are most likely to use AI
Analyze developer sentiment and perceived threat toward AI
Examine AI’s impact on work patterns, salary, and job satisfaction
Build machine learning models to predict AI usage

📊 Dataset

Source: Stack Overflow Developer Surveys (2022–2025)
Participants: Global software developers across roles, experience levels, and regions
Target Variable: UsesAI (whether a developer uses AI tools)
Due to changes in survey structure across years, data was cleaned and harmonized to enable meaningful comparisons.

🔍 Methodology

The analysis follows an end-to-end data analytics workflow:

Data Cleaning & Harmonization
Standardized columns across years
Handled missing values and inconsistent labels
Exploratory Data Analysis (EDA)
AI adoption trends over time
Developer sentiment and threat perception
Primary AI use cases
Impact on work style and job satisfaction
Trend & Comparative Analysis
Year-by-year comparison (2022 → 2025)
Adoption acceleration and maturity phases
Machine Learning Modeling
Predict AI usage using developer profile data
Compare multiple classification models

🤖 Machine Learning Models

Two models were trained and evaluated:

Logistic Regression

Chosen for interpretability

Helps understand which factors influence AI adoption

Random Forest Classifier

Captures non-linear patterns

Used to validate robustness and performance

🔑 Input Features

Experience (YearsCode)

Salary (ConvertedCompYearly)

Remote work status

Developer role

AI sentiment score

Education level

📈 Performance (Approx.)

Accuracy: ~80%

Key Insight: AI adoption is predictable, not random

📌 Key Insights

AI adoption accelerated sharply during 2023–2024

Developers primarily use AI for coding, debugging, and documentation

Fear of AI remains low, even as adoption increases

AI does not immediately increase salary

AI users report slightly higher job satisfaction

By 2025, developers show a mature, selective approach, especially toward AI agents

🧠 Final Conclusion

AI has not replaced developers.
It has become a trusted productivity layer, and developers are adapting with confidence — not fear.

This project demonstrates how data analytics and machine learning can be combined with clear storytelling to generate practical, real-world insights.

🛠️ Tech Stack

Python

Pandas, NumPy

Matplotlib

Scikit-learn

Jupyter Notebook

📁 Repository Structure
ai-adoption-analysis-2022-2025/
│
├── notebooks/
│   └── analysis.ipynb
├── plots/
│   └── slide_charts/
├── presentation.pdf
├── README.md

🚀 How to Use

Clone the repository

Open analysis.ipynb to explore the analysis and models

View presentation.pdf for the executive-style summary

📬 Contact

If you’d like to discuss this project or collaborate, feel free to connect with me on LinkedIn or explore my portfolio.
