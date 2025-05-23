<h1 align="center">🚀 Credit Card Fraud Detection using Machine Learning Models</h1>
A project to detect Credit Card Fraud using Machine Learning Models like Logistic Regression, Decision Tree, KNN, and Random Forest Model, involving preprocessing steps such as feature scaling and data balancing to enhance performance, where each model is evaluated using key metrics to determine its effectiveness in accurately identifying fraudulent transactions.
<h2>📌 Project Overview</h2>
<p>
  This project focuses on detecting fraudulent credit card transactions using multiple machine learning models. Given the significant class imbalance in real-world fraud data, SMOTE (Synthetic Minority Over-sampling Technique) is used to balance the dataset.
</p>

<h2>📂 Dataset Information</h2>
<ul>
  <li><b>Source:</b> <a href="https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud">Kaggle - Credit Card Fraud Detection</a></li>
  <li><b>Features:</b> Time, Amount, V1-V28 (PCA-transformed)</li>
  <li><b>Target:</b> Class (0 = Legitimate, 1 = Fraudulent)</li>
</ul>

<h2>🛠️ Setup Instructions</h2>
<h3>1️⃣ Install Dependencies</h3>
<pre>
pip install pandas numpy scikit-learn imbalanced-learn matplotlib seaborn joblib
</pre>

<h3>2️⃣ Download the Dataset</h3>
<p>Ensure <code>creditcard.csv</code> is placed in the working directory.</p>

<h3>3️⃣ Run the Models</h3>
<p>The script includes Logistic Regression, Random Forest, Decision Tree, and K-Nearest Neighbors models.</p>

<h2>📊 Data Preprocessing & Feature Engineering</h2>
<ul>
  <li><b>Scaling Features:</b> Using <code>StandardScaler</code></li>
  <li><b>Handling Imbalance:</b> Using <code>SMOTE</code></li>
  <li><b>Train-Test Split:</b> 80% training, 20% testing</li>
</ul>

<h2>🤖 Trained Models & Evaluation</h2>

<ul>
  <li><b>Model:</b></li>
  <ul>
    <li>Logistic Regression</li>
    <li>Random Forest</li>
    <li>KNN</li>
    <li>Decision Tree</li>
  </ul>
  <li><b>Evaluation Metrics:</b></li>
  <ul>
    <li>Accuracy, Precision, Recall, F1-score</li>
    <li>Confusion Matrix, ROC Curve</li>
  </ul>
</ul>

<h2>📉 Model Performance Comparison Chart</h2>

<p align="center">
  <img src="Comparision of all ML Models.png" alt="Model Comparison Chart" width="700"/>
</p>

<h2>🏆 Best Performing Model: Random Forest</h2>
<ul>
  <li><b>Accuracy:</b> <b>99.9%</b></li>
  <li><b>Recall:</b> <b>0.82</b></li>
  <li><b>F1-Score:</b> <b>0.83</b></li>
  <li><b>Precision:</b> <b>0.85</b></li>
  <li><b>AUC-ROC:</b> <b>0.97</b></li>
</ul>

<h2>📉 Confusion Matrix (Sample Format)</h2>
<table>
  <tr>
    <th></th>
    <th>Predicted Legit (0)</th>
    <th>Predicted Fraud (1)</th>
  </tr>
  <tr>
    <td><b>Actual Legit (0)</b></td>
    <td>TN</td>
    <td>FP</td>
  </tr>
  <tr>
    <td><b>Actual Fraud (1)</b></td>
    <td>FN</td>
    <td>TP</td>
  </tr>
</table>

<h2>📦 Model Deployment</h2>
<p>Model can be saved using <code>joblib</code> and deployed in a Flask or Streamlit web application.</p>

<h2>📚 References</h2>
<ul>
  <li><a href="https://scikit-learn.org/">Scikit-Learn Documentation</a></li>
  <li><a href="https://imbalanced-learn.org/">Imbalanced-Learn Documentation</a></li>
</ul>

<h2>👨‍💻 Author</h2>
<p>🚀 <b>M.Rakesh Dora</b> | 🌍 GitHub: <a href="https://github.com/Rakesh5862">GitHub</a> | 🔗 LinkedIn: <a href="http://linkedin.com/in/m-rakesh-dora-5a9b4a290">LinkedIn</a></p>

