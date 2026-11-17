# Student Performance Analysis

## Project Overview
This project explores factors associated with students' mathematics performance and uses machine learning models to predict final mathematics grades.

The analysis uses the Student Performance dataset from the UCI Machine Learning Repository.

## Objectives
- Explore the relationship between student characteristics and academic performance.
- Analyse the effect of study time and previous failures on final grades.
- Build machine learning models to predict students' final mathematics grades.
- Compare the performance of Linear Regression and Random Forest Regression.

## Dataset
- **Source:** [UCI Student Performance Dataset](https://archive.ics.uci.edu/dataset/320/student+performance)
- **Observations:** 395 students
- **Features:** 33 columns
- **Target variable:** G3 (final mathematics grade)

## Tools and Technologies
- Python
- Pandas and NumPy
- Matplotlib and Seaborn
- Scikit-learn
- Google Colab

## Key Findings
- Students with more previous failures generally had lower final grades.
- Study time showed some positive association with performance, although the relationship was not strictly increasing across all categories.
- Absences had a very weak linear correlation with final grades in this dataset.

## Model Performance

Two regression models were evaluated using an 80:20 train-test split.

| Model | MAE | RMSE | R² Score |
|---|---:|---:|---:|
| Linear Regression | 1.647 | 2.378 | 0.724 |
| Random Forest | 1.201 | 2.015 | 0.802 |

Random Forest performed better than Linear Regression on the test set.

## Limitations
- The dataset contains only 395 observations from two Portuguese schools.
- Results may not generalise to students in other countries or educational systems.
- The models use first- and second-period grades (G1 and G2), so they are not intended to predict performance at the beginning of the academic year.
- Evaluation is based on one train-test split.

## Conclusion
This project demonstrates how exploratory data analysis and machine learning can be used to investigate academic performance. Random Forest achieved the better test-set results among the two models evaluated.

## Author
**Dishita Dutta**  
[LinkedIn](https://www.linkedin.com/in/dishitadutta/) | [GitHub](https://github.com/dishitadutta)
