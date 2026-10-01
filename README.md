# Student Depression Prediction Using Machine Learning

## Why This Project?

Student mental health is an important issue, as academic demands, financial stress, lifestyle factors, and other circumstances can affect students' well-being. I chose to explore this topic to investigate whether patterns in these factors could be used to better understand and predict depression status among students.

As part of the 2026 BRICS Astronomy Data Analytics Course, I wanted to apply machine learning to a real-world problem outside of my usual astronomy research. For my capstone project, I chose to explore student depression as an opportunity to test my skills in exploratory data analysis, machine learning, and interpreting and comparing model results.

## Objective

The objective of this project was to investigate factors associated with student depression and evaluate whether machine learning models could predict depression status.

## Dataset

The dataset contains **502 student observations and 11 features**, covering demographic, academic, financial, and lifestyle characteristics. The dataset was downloaded from **Kaggle**. The target variable is **Depression (Yes/No)**.

## Analysis

The project included:

- Data inspection and preprocessing
- Exploratory data analysis (EDA)
- Categorical variable encoding
- Feature scaling
- Train/test splitting
- Machine learning model training and evaluation

The following models were evaluated:

- Logistic Regression
- Random Forest
- Decision Tree

## Key Insights

The exploratory analysis showed several patterns associated with depression:

- The exploratory analysis indicates that academic pressure, study satisfaction, financial stress, suicidal thoughts, dietary habits, and study hours showed notable associations with depression in this dataset.
- Healthy lifestyle behaviours were generally associated with lower levels of depression.

## Model Results

| Model               | Accuracy |
| ------------------- | -------: |
| Logistic Regression |    94.1% |
| Random Forest       |    94.1% |
| Decision Tree       |    89.1% |

Logistic Regression and Random Forest achieved the same overall accuracy of **94.1%**. Logistic Regression produced fewer false negatives in the test set, while also providing a more interpretable model.

Decision Tree achieved a lower accuracy of **89.1%**.

## Takeaways

This project strengthened my ability to apply machine learning to a real-world dataset, interpret patterns in the data, and evaluate and compare classification models. It also highlighted the importance of looking beyond model accuracy when interpreting machine learning results.

## Tools

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Google Colab

## Project File

- [Student_depression-ML.ipynb](Student_depresssion-ML.ipynb) — complete analysis, visualisations, preprocessing, and machine learning modelling.

## Note

This project demonstrates the application of exploratory data analysis and supervised machine learning to a student mental health dataset. The results should not be interpreted as a clinical diagnostic tool.
