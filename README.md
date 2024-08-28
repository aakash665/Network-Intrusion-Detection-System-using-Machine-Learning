# Network-Intrusion-Detection-System-using-Machine-Learning
This repository contains a comprehensive implementation of a Network Intrusion Detection System (NIDS) leveraging machine learning techniques. The system aims to detect and classify network intrusions in real-time, providing a robust defense mechanism against potential cyber threats.

## Results

| Model               | Train Score | Test Score |
|---------------------|-------------|------------|
| KNN                 | 0.984972    | 0.981477   |
| Logistic Regression | 0.941477    | 0.941651   |
| Decision Tree       | 0.999887    | 0.995237   |
| Random Forest       | 0.999773    | 0.995105   |
| GBM                 | 0.99535     | 0.992723   |
| XGBM                | 0.999887    | 0.996692   |
| Adaboost            | 0.981456    | 0.983594   |
| Light GBM           | 0.999887    | 0.99656    |
| CatBoost            | 0.998412    | 0.995634   |
| Naive Bayes Model   | 0.89214     | 0.892564   |
| Voting              | 0.999887    | 0.996295   |
| SVM                 | 0.970965    | 0.973406   |


## Tech Stack

### Programming Languages and Libraries
- 🐍 **Python**: Core programming language.
- 🔢 **NumPy**: For numerical computations.
- 📊 **Pandas**: For data manipulation and analysis.
- 📈 **Seaborn**: For data visualization.
- 📉 **Matplotlib**: For plotting graphs.
- 📝 **Tabulate**: For creating tabular data.

### Machine Learning Libraries
- 🤖 **Scikit-learn**: Machine learning library for data preprocessing, model selection, and evaluation.
  - 🌳 `tree`, `train_test_split`, `StandardScaler`, `LabelEncoder`, `RFE`
  - 📉 `LogisticRegression`, `KNeighborsClassifier`, `DecisionTreeClassifier`
  - 🌲 `RandomForestClassifier`, `AdaBoostClassifier`, `VotingClassifier`, `GradientBoostingClassifier`
  - 💻 `SVC`, `LinearSVC`, `BernoulliNB`

### Advanced Machine Learning Models
- ⚡ **LightGBM**: Gradient boosting framework.
- 🐱 **CatBoost**: Gradient boosting on decision trees library.
- 🚀 **XGBoost**: Extreme Gradient Boosting library.

### Hyperparameter Optimization
- 🎯 **Optuna**: For hyperparameter optimization.

### Utilities
- 💾 **Joblib**: For model persistence.



## Dataset Features


- duration
- protocol_type
- service
- flag
- src_bytes

- dst_bytes
- land
- wrong_fragment
- urgent
- hot

- num_failed_logins
- logged_in
- num_compromised
- root_shell
- su_attempted

- num_root
- num_file_creations
- num_shells
- num_access_files
- num_outbound_cmds

- is_host_login
- is_guest_login
- count
- srv_count
- serror_rate

- srv_serror_rate
- rerror_rate
- srv_rerror_rate
- same_srv_rate
- diff_srv_rate

- srv_diff_host_rate
- dst_host_count
- dst_host_srv_count
- dst_host_same_srv_rate
- dst_host_diff_srv_rate

- dst_host_same_src_port_rate
- dst_host_srv_diff_host_rate
- dst_host_serror_rate
- dst_host_srv_serror_rate
- dst_host_rerror_rate

- dst_host_srv_rerror_rate
- class (Target Variable)

