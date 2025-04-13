**Credit Approval Predictor**
This project aims to predict the likelihood of credit approval for borrowers based on various financial and personal attributes. The process involves data cleaning, exploratory data analysis (EDA), model training, hyperparameter tuning using GridSearchCV.

**Problem Statement**
The objective is to develop a predictive model that can assess the risk associated with loan applicants and classify them into different risk categories (e.g., P1, P2, P3, P4) based on their likelihood of credit approval. This will aid financial institutions in making informed decisions while approving loans, thereby minimizing the risk of default and optimizing their lending processes.

**Data Cleaning**
The dataset undergoes thorough data cleaning processes, including handling missing values, removing duplicates, encoding categorical variables, and scaling numerical features. This ensures the data is suitable for model training and analysis.

**Exploratory Data Analysis (EDA)**
EDA is performed to gain insights into the dataset's characteristics and relationships between variables. Visualizations such as histograms, box plots, and correlation matrices are used to understand the distribution of features, identify patterns, and detect anomalies.

**Model Training**
Various machine learning models are trained on the cleaned dataset to predict credit approval. The models include logistic regression, decision trees, random forests, and gradient boosting classifiers. Performance metrics such as accuracy, precision, recall, and F1-score are used to evaluate the models.XgBoost  performed best giving 78% accuracy

**Hyperparameter Tuning**
GridSearchCV is employed to fine-tune the hyperparameters of the selected model(s) and optimize their performance. This process involves systematically searching through a range of hyperparameter values to identify the best combination that maximizes the model's predictive accuracy.

