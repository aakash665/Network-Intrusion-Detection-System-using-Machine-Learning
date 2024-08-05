# Network-Intrusion-Detection-System-using-Machine-Learning
This repository contains a comprehensive implementation of a Network Intrusion Detection System (NIDS) leveraging machine learning techniques. The system aims to detect and classify network intrusions in real-time, providing a robust defense mechanism against potential cyber threats.

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

