<h1 align="center">AI-Powered Customer Retention Prediction System</h1>

<p align="center">
  A Machine Learning based project to predict customer churn and help businesses improve retention strategies.
</p>

<hr>

<h2>📌 Project Overview</h2>
<p>
Customer churn significantly impacts business revenue and growth. This project focuses on building an
AI-powered system that predicts whether a customer is likely to churn based on demographic, service,
and billing information using machine learning techniques.
</p>

<h2>🏗️ Architecture</h2>
<p>
The system follows a complete machine learning pipeline including data preprocessing, feature engineering,
model training, evaluation, and deployment using a Flask web application.
</p>

<h2>📊 Data Visualization</h2>
<ul>
  <li>Partner distribution</li>
  <li>Churn distribution</li>
  <li>Tenure vs churn</li>
  <li>Monthly charges vs churn</li>
  <li>Contract type analysis</li>
  <li>SIM provider and service usage analysis</li>
</ul>

<h2>🧹 Feature Engineering</h2>
<p>
Feature engineering was performed to improve model performance and data quality.
</p>
<ul>
  <li>Handling missing values (Iterative Imputer – Best)</li>
  <li>Data separation (categorical & numerical)</li>
  <li>Variable transformation (Yeo–Johnson – Best)</li>
  <li>Outlier handling (Winsorization – Best)</li>
</ul>

<h2>🔎 Handling Missing Values</h2>
<ul>
  <li>Random Sample Imputation</li>
  <li>Mean / Median / Mode Imputation</li>
  <li>KNN Imputer</li>
  <li>Iterative Imputer (Selected)</li>
  <li>Dropping Missing Data</li>
</ul>

<h2>🔄 Variable Transformation</h2>
<ul>
  <li>Power Transformation</li>
  <li>Box-Cox Transformation</li>
  <li>Log Transformation</li>
  <li>Arcsin Transformation</li>
  <li><b>Yeo–Johnson Transformation (Best)</b></li>
</ul>

<h2>🚨 Outlier Handling</h2>
<ul>
  <li>Outlier Capping</li>
  <li>Outlier Trimming</li>
  <li>5th and 95th Quantile</li>
  <li><b>Winsorization (Best)</b></li>
</ul>

<h2>🎯 Feature Selection</h2>
<ul>
  <li>One-Hot Encoding</li>
  <li>Ordinal Encoding</li>
  <li>Label Encoding</li>
  <li>Filter Methods</li>
  <li>Chi-Square Test (Best)</li>
</ul>

<h2>⚖️ Data Balancing</h2>
<p>
SMOTE (Synthetic Minority Oversampling Technique) was used to handle class imbalance and improve
minority class prediction.
</p>

<h2>📏 Feature Scaling</h2>
<p>
StandardScaler (Z-score normalization) was applied to ensure all numerical features are on the same scale,
improving convergence and model performance.
</p>

<h2>🤖 Model Training</h2>
<ul>
  <li>Logistic Regression</li>
  <li>Decision Tree</li>
  <li>Random Forest</li>
  <li>XGBoost</li>
  <li>Support Vector Machine</li>
</ul>

<h2>📈 Model Evaluation</h2>
<p>
Models were evaluated using Accuracy, Precision, Recall, F1-score, ROC Curve, and AUC Score.
Logistic Regression achieved the best AUC score and was selected as the final model.
</p>

<h2>⚙️ Hyperparameter Tuning</h2>
<p>
GridSearchCV was used to optimize hyperparameters and improve the final model’s performance.
</p>

<h2>🚀 Deployment</h2>
<p>
The final trained model was deployed using a Flask web application that allows real-time customer churn
prediction through user input.
</p>

<h2>📌 Results</h2>
<p>
The final Logistic Regression model achieved approximately <b>75% accuracy</b> and effectively predicts
customer churn.
</p>

<h2>✅ Conclusion</h2>
<p>
This project demonstrates how machine learning can be applied to predict customer churn and support
data-driven business decisions. The system helps organizations proactively identify at-risk customers and
improve retention strategies.
</p>

<h2>🔮 Future Enhancements</h2>
<ul>
  <li>Integrate deep learning models (ANN, CNN, LSTM)</li>
  <li>Enable real-time data pipelines</li>
  <li>Develop advanced visual analytics dashboards</li>
</ul>

<h2>📚 References</h2>
<ul>
  <li><a href="https://www.kaggle.com/datasets/blastchar/telco-customer-churn">Kaggle – Telco Customer Churn</a></li>
  <li><a href="https://feature-engine.trainindata.com/">Feature Engine Documentation</a></li>
  <li><a href="https://scikit-learn.org/">Scikit-learn Documentation</a></li>
</ul>

<hr>

<p align="center">
  <b>Author:</b> Govula Meenu<br>
  <b>Domain:</b> Data Science | Machine Learning
</p>
