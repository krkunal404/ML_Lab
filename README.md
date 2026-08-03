<div align="center">

# 🤖 ML_Lab

### Machine Learning Lab Repository

*Hands-on labs, notebooks, and class activities from the Machine Learning course* 📊🧠

![Python](https://img.shields.io/badge/Python-3.x-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-F37626?style=for-the-badge&logo=jupyter&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-ML-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-Data-150458?style=for-the-badge&logo=pandas&logoColor=white)
![Status](https://img.shields.io/badge/Status-Active-brightgreen?style=for-the-badge)

</div>

---

## 📅 Lab Log

<table>
<tr>
<th>🧪 Lab</th>
<th>🗓️ Date</th>
<th>🎯 Topic</th>
<th>📝 What was done</th>
</tr>

<tr>
<td><b><a href="Lab%201%20%262/">Lab 1 & 2</a></b><br>📊</td>
<td>2026-06-09<br><sub>09:46</sub></td>
<td>Data Visualisation<br>& Exploration</td>
<td>Loaded <code>city_day.csv</code> &amp; <code>crop_production.csv</code>; explored shape, columns, dtypes, summary stats, and missing values; visualized distributions with <code>matplotlib</code>/<code>seaborn</code>.</td>
</tr>

<tr>
<td><b><a href="lab%203/">Lab 3</a></b><br>📈</td>
<td>2026-06-16<br><sub>11:39</sub></td>
<td>Simple Linear<br>Regression</td>
<td>Preprocessed <code>class_survey.csv</code>; trained a <code>LinearRegression</code> model with Scikit-Learn, then manually derived the line using <b>Ordinary Least Squares (OLS)</b> to compare against the library result; persisted model weights with <code>pickle</code>.</td>
</tr>

<tr>
<td><b><a href="Lab%204/">Lab 4</a></b><br>🌲</td>
<td>2026-07-04<br><sub>21:28</sub></td>
<td>KNN Classification<br>& PCA</td>
<td>Explored the Breast Cancer dataset; scaled features with <code>StandardScaler</code>; tuned <code>KNeighborsClassifier</code> across values of <i>k</i>; applied <code>PCA</code> for dimensionality reduction and built a scaler + KNN pipeline; evaluated with accuracy, confusion matrix &amp; classification report.</td>
</tr>

<tr>
<td><b><a href="Lab%205/">Lab 5</a></b><br>🎓</td>
<td>2026-07-21<br><sub>19:52</sub></td>
<td>Regression on Student<br>Performance Data</td>
<td>Explored <code>student-mat.csv</code>; checked nulls/duplicates; preprocessed &amp; scaled features; trained a regression model; evaluated with <b>MSE</b> and <b>R² score</b>.</td>
</tr>

<tr>
<td><b><a href="Lab%206/">Lab 6</a></b><br>⚖️</td>
<td>2026-07-21<br><sub>23:08</sub></td>
<td>Logistic Regression<br>vs KNN</td>
<td>Explored the Breast Cancer dataset; scaled features; trained &amp; compared <code>LogisticRegression</code> and <code>KNeighborsClassifier</code>; evaluated with accuracy, confusion matrix &amp; classification report.</td>
</tr>

<tr>
<td><b><a href="lab%207/">Lab 7</a></b><br>🌳</td>
<td>2026-07-27<br><sub>15:46</sub></td>
<td>Decision Trees</td>
<td>Visualized the Iris dataset; trained <code>DecisionTreeClassifier</code> models (Gini vs. entropy); tuned <code>max_depth</code>, <code>min_samples_split</code>, <code>min_samples_leaf</code>; ran a grid search for optimal params; visualized the tree and evaluated results.</td>
</tr>

<tr>
<td><b><a href="Lab%208/">Lab 8</a></b><br>🃏</td>
<td>2026-08-03<br><sub>17:13</sub></td>
<td>Model Comparison<br>on Categorical Data</td>
<td>Preprocessed the <code>Play Tennis</code> dataset with <code>LabelEncoder</code>; trained &amp; compared <code>CategoricalNB</code>, <code>DecisionTreeClassifier</code>, <code>LogisticRegression</code> &amp; <code>SVC</code>; evaluated accuracy, confusion matrix &amp; classification report; ran single-sample inference across all models.</td>
</tr>

</table>

---

## 🗂️ Repository Structure

```
ML_Lab/
├── 📁 Lab 1 &2/           → Notebook, script & datasets — data visualisation
├── 📁 lab 3/              → Notebook, script & saved weights — linear regression
├── 📁 Lab 4/              → Notebook & script — KNN classification + PCA
├── 📁 Lab 5/              → Notebook & script — regression on student data
├── 📁 Lab 6/              → Notebook & script — logistic regression vs KNN
├── 📁 lab 7/              → Notebook & script — decision trees
├── 📁 Lab 8/              → Notebook & script — Naive Bayes vs DT vs LR vs SVM
└── 📁 Lab Manual/         → Course lab manual (.docx)
```

---

## 🧰 Tools & Libraries

<div align="center">

![NumPy](https://img.shields.io/badge/-NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![Pandas](https://img.shields.io/badge/-Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![Matplotlib](https://img.shields.io/badge/-Matplotlib-11557C?style=flat-square&logo=plotly&logoColor=white)
![Seaborn](https://img.shields.io/badge/-Seaborn-3776AB?style=flat-square)
![scikit-learn](https://img.shields.io/badge/-scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)

</div>

**Algorithms covered:** Linear Regression · Manual OLS · Logistic Regression · K-Nearest Neighbors · Decision Trees · PCA · Naive Bayes · SVM

**Evaluation metrics:** Accuracy · Confusion Matrix · Classification Report · MSE · R² Score

---

<div align="center">

✨ *Maintained as part of ongoing ML coursework* ✨

</div>
