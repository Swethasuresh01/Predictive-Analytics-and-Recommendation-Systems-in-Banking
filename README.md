# Predictive-Analytics-and-Recommendation-Systems-in-Banking

**Introduction:**
---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
* This project focuses on prediting Loan Defaults using Supervised Learning, Segmenting Customers with Unsupervised Learning, and Recommending Bank Products through a Recommendation Engine.

**Technologies Used:**
---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
* Python
* Pandas
* NumPy
* Scikit-learn
* Matplotlib
* Seaborn
* Streamlit
* Pickly
* Scipy
* Surprise

**Installation:**
---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
* pip install pandas
* pip install numpy
* pip install scikit-learn
* pip install matplotlib
* pip install seaborn
* pip install streamlit
* pip install pickle
* pip install scikit-surprise

**Data Collection:**
---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
* Synthetic data is generated using the Faker Python library

* Loan Default Prediction: Customer demographics, loan amounts, interest rates, and repayment status.
* Customer Segmentation: Transaction details including amounts, types, and dates.
* Loan Default Prediction: Customer interactions with various banking products.

**Data Understanding:**
---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
* Identify Variable Types
* Handle Invalid Values

**Data Preprocessing:**
---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
* Handle Missing Values using Mean, Median, Mode.
* Detect Outliers using IQR or Isolation Forest.
* Determine Skewness Using Log, sqrt or Box-Cox transformations.
* Encode Categorical Variables with One-Hot Encoding, Label Encoding, or Ordinal Encoding.

**Exploratory Data Analysis:**
---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
* Visualize Outliers and Skewness with Boxplot, Distplot or Violin plots.
* Analyze and Treat Skewness.

**Feature Engineering:**
---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
* Create New Features through Aggregation or Transformation.
* Drop highly correlated columns using heatmaps.

**Model Building and Evaluation:**
---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
* Split Data
* Model Training and Evaluate: ** Loan Default Prediction: Use Classification models-Logistic Regression, Decision Tree Classifer, Random Forest Classifier, Gradient Boosting. Metrics: Accuracy, Precision, Recall, F1 score. ** Customer Segmentations: Use Clustering Algorithms-KMeans, DBscan, Hierarchical Clustering to segment customers based on transaction behavior. Metrics: Silhoutte scores and Davies-Bouldin index to evaluate cluster quality. ** Product Recommendations: Use Collabarative filtering or Content-Based Filtering Algorithms. Metrics: Precision, Recall, Mean Average Precision(MAP), Normalized Discounted Cumulative Gain score.
Optimize with Hyperparameter Tuning: Use Cross-Validation and Grid Search.

**Model GUI:**
---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
* Develop a Streamlit App for interactive predictions, customer segmentations and product recommendations.
* Allow the users to input feature values and display predictions, customer segmentations and product recommendations.
**Usage:**
* Run the App locally streamlit run bank.py
* Expose the App to the Internet Using ngrok.
* Install pyngrok: pip install pyngrok
* Add your ngrok authentication token and include the following snippet in your script: from pyngrok import ngrok ngrok.set_auth_token("your_ngrok_token") public_url = ngrok.connect(8501) print(f"Access your app
* here: {public_url}") The app will now be accessible via the generated public URL.
* Explore Online Streamlit App: You can access the live application hosted at: https://086e-34-73-124-243.ngrok-free.app/ 
