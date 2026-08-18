# ML_Lab

Notebooks and code from my Machine Learning course labs. Each folder is one lab session — dataset(s), a notebook, and usually a plain script version too.

## Labs

| # | Topic | What I did |
|---|-------|------------|
| [1 & 2](Lab%201%20%262/) | Data visualisation & exploration | Loaded `city_day.csv` and `crop_production.csv`, checked shape/dtypes/missing values, plotted distributions with matplotlib and seaborn |
| [3](lab%203/) | Simple linear regression | Fit `LinearRegression` on `class_survey.csv`, then derived the same line by hand with OLS to check the library's answer; saved the model with pickle |
| [4](Lab%204/) | KNN + PCA | Scaled the Breast Cancer dataset, tuned k for `KNeighborsClassifier`, reduced dimensions with PCA, evaluated with accuracy/confusion matrix/classification report |
| [5](Lab%205/) | Regression on student performance | Cleaned `student-mat.csv` (nulls, duplicates), scaled features, trained a regression model, checked MSE and R² |
| [6](Lab%206/) | Logistic regression vs KNN | Same Breast Cancer dataset, compared the two classifiers head to head |
| [7](lab%207/) | Decision trees | Iris dataset, Gini vs entropy, grid search over max_depth / min_samples_split / min_samples_leaf, plotted the resulting tree |
| [8](Lab%208/) | Naive Bayes, DT, LR, SVM comparison | Encoded the Play Tennis dataset and compared `CategoricalNB`, `DecisionTreeClassifier`, `LogisticRegression`, and `SVC` on accuracy + single-sample predictions |
| [9](Lab%209/) | SVM, PCA & LDA | Applied SVM (linear/RBF tuned with GridSearchCV) on Breast Cancer dataset; reduced dimensionality of Wine dataset using PCA & supervised LDA, evaluating explained variance and decision boundaries |
| [10](lab%2010/) | XOR with an MLP (Keras, TensorFlow, PyTorch) | Solved the non-linearly-separable XOR problem with a 2-4-1 MLP, implementing it three ways (Keras `Sequential`, low-level TensorFlow with `GradientTape`, and PyTorch), then compared training curves, decision boundaries, and the effect of learning rate |

## Structure

```
ML_Lab/
├── Lab 1 &2/       data viz
├── lab 3/          linear regression
├── Lab 4/          KNN + PCA
├── Lab 5/          regression
├── Lab 6/          logistic regression vs KNN
├── lab 7/          decision trees
├── Lab 8/          Naive Bayes vs DT vs LR vs SVM
├── Lab 9/          SVM, PCA & LDA
├── lab 10/         XOR with an MLP (Keras, TensorFlow, PyTorch)
└── Lab Manual/     course manual (.docx)
```

## Stack

Python, pandas, NumPy, scikit-learn, matplotlib, seaborn, TensorFlow/Keras, PyTorch — mostly run through Jupyter notebooks.
