**Decision Tree Classification — Personal Loan Prediction**

**Overview:** Built and evaluated Decision Tree classifiers to predict which bank customers are likely to accept a personal loan offer, using Thera Bank's customer dataset. Includes comparison of splitting criteria and multiple pruning strategies to combat overfitting.

**Problem:** Predict Personal Loan acceptance (binary target) from customer demographic and financial attributes (age, income, education, family size, mortgage, credit card spending, existing account types, etc.) to help the bank better target marketing campaigns and improve conversion rates.

**Key Steps**
EDA: Duplicate and missing value detection/treatment, boxplot-based outlier analysis, scatter plot matrix, and correlation heatmap across features
Preprocessing: One-hot encoding for multi-category features (ColumnTransformer/get_dummies); stratified 80/20 train-test split with fixed random seed
Model building: Trained and compared Decision Trees using Gini Impurity and Entropy splitting criteria; visualized fully-grown trees with labeled features
Evaluation: Compared models on execution time, accuracy, and confusion matrices; analyzed how training set size affects performance
Pruning: Implemented and tuned three pruning strategies via 5-fold cross-validation:
Maximum depth limiting
Minimum samples per split
Cost-complexity pruning (alpha selection)
Compared pruned vs. fully-grown trees on accuracy and runtime; visualized all resulting trees
Addressed class imbalance and evaluated feature importance

Tech stack: Python, Pandas, NumPy, scikit-learn, Seaborn/Matplotlib

[View the Project in Document format](Assignment2_Group1.pdf)
