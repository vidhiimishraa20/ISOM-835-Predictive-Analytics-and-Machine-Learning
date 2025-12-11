<h1 align="center">Telco Customer Churn Prediction</h1>

<p align="center">
  Predictive analytics project applying full EDA, preprocessing, and machine learning models to forecast telecom customer churn.
</p>

---

<h2>📌 Project Summary</h2>
<p>
This project analyzes the IBM Telco Customer Churn dataset to understand churn behavior and build machine learning models that can predict which customers are likely to leave. The workflow includes exploratory data analysis, cleaning, preprocessing, model development, and interpretability.
</p>

---

<h2>🎯 Objectives</h2>
<ul>
  <li>Identify customer characteristics associated with churn.</li>
  <li>Build and evaluate predictive models to estimate churn probability.</li>
  <li>Compare multiple algorithms and select the best-performing model.</li>
  <li>Interpret important features influencing churn to support business decisions.</li>
</ul>

---

<h2>📊 Dataset Description</h2>
<ul>
  <li><b>Dataset:</b> WA_Fn-UseC_-Telco-Customer-Churn.csv</li>
  <li><b>Source:</b> IBM Sample Data via Kaggle</li>
  <li><b>Rows:</b> 7,043 entries (7,032 after cleaning)</li>
  <li><b>Features:</b> Demographics, service usage, billing information, and customer contract details</li>
  <li><b>Target:</b> Churn (Yes/No)</li>
</ul>

---

<h2>🛠 Tools & Libraries</h2>
<ul>
  <li><code>Python</code></li>
  <li><code>pandas</code>, <code>numpy</code></li>
  <li><code>matplotlib</code>, <code>seaborn</code></li>
  <li><code>scikit-learn</code> — preprocessing, modeling, and evaluation</li>
  <li>Google Colab environment</li>
</ul>

---

<h2>📒 Colab Notebook</h2>
<p>
<a href="https://colab.research.google.com/drive/1dUPbpn3GICESx1k4eQneFkQdDwFJOjQ1?usp=sharing" target="_blank">Click here to open the full analysis notebook in Google Colab</a>
</p>

---

<h2>▶️ How to Run the Analysis</h2>

<h3>Option A: Run in Google Colab</h3>
<ol>
  <li>Open the notebook using the link above.</li>
  <li>Upload the dataset or mount Google Drive:
<pre>
from google.colab import drive
drive.mount('/content/drive')
</pre>
  </li>
  <li>Update the file path in <code>pd.read_csv()</code> if needed.</li>
</ol>

<h3>Option B: Run Locally</h3>
<pre>
git clone https://github.com/&lt;your-username&gt;/&lt;your-repo&gt;.git
cd &lt;your-repo&gt;
pip install -r requirements.txt
jupyter notebook
</pre>

<p>Open the notebook file and ensure the dataset CSV is in the project folder or update the file path accordingly.</p>
