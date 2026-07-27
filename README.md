# ML_Lab

Machine Learning Lab repository — coursework, lab exercises, and class activities for the Machine Learning course.

## Lab Log

| Lab | Date | Topic | What was done |
|-----|------|-------|----------------|
| [Lab 1 & 2](Lab%201%20%262/) | 2026-06-09 09:46 | Data Visualisation & Exploration | Loaded `city_day.csv` and `crop_production.csv`; explored shape, columns, dtypes, summary stats, and missing values; visualized distributions with `matplotlib`/`seaborn`. |
| [Lab 3](lab%203/) | 2026-06-16 11:39 | Simple Linear Regression | Preprocessed `class_survey.csv`; trained a `LinearRegression` model with Scikit-Learn, then manually derived the regression line using Ordinary Least Squares (OLS) to compare against the library implementation; persisted model parameters with `pickle`. |
| [Lab 4](Lab%204/) | 2026-07-04 21:28 | KNN Classification & PCA | Explored the Breast Cancer dataset; scaled features with `StandardScaler`; tuned and evaluated a `KNeighborsClassifier` across different `k` values; applied `PCA` for dimensionality reduction and built a scaler+KNN pipeline; assessed results with accuracy, confusion matrix, and classification report. |
| [Lab 5](Lab%205/) | 2026-07-21 19:52 | Regression on Student Performance Data | Explored `student-mat.csv`; checked for nulls/duplicates; preprocessed and scaled features; trained a regression model and evaluated it with MSE and R² score. |
| [Lab 6](Lab%206/) | 2026-07-21 23:08 | Logistic Regression vs KNN | Explored the Breast Cancer dataset; scaled features; trained and compared `LogisticRegression` and `KNeighborsClassifier` models using accuracy, confusion matrix, and classification report. |
| [Class Activity](Class%20Activity/) | 2026-07-27 15:46 | Decision Trees | Visualized the Iris dataset; trained `DecisionTreeClassifier` models (Gini vs. entropy criteria); tuned `max_depth`, `min_samples_split`, and `min_samples_leaf`; ran a grid search for optimal parameters; visualized the resulting tree and evaluated with accuracy, confusion matrix, and classification report. |

## Repository Structure

- `Lab 1 &2/` — Notebook, script, and datasets for Labs 1 & 2
- `lab 3/` — Notebook, script, and saved model weights for Lab 3
- `Lab 4/` — Notebook and script for Lab 4
- `Lab 5/` — Notebook and script for Lab 5
- `Lab 6/` — Notebook and script for Lab 6
- `Class Activity/` — Notebook and script for the in-class Decision Tree activity
- `Lab Manual/` — Course lab manual

## Tools & Libraries

`pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn` (`LinearRegression`, `LogisticRegression`, `KNeighborsClassifier`, `DecisionTreeClassifier`, `StandardScaler`, `PCA`, `train_test_split`, model evaluation metrics)
