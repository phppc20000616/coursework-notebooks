# Applied Data Science — Python

Implementations and analyses from ECE 4710J (Applied Data Science) at Shanghai Jiao Tong University, covering exploratory data analysis, machine learning pipelines, classification, regression, and SQL-based data querying.

---

## Projects

### [Taxi Rider Retention](taxi-rider-retention/)
Predictive modeling competition to identify riders likely to churn from a ride-sharing platform. Trained a gradient-boosted classifier on behavioral and demographic features; submitted final predictions via Kaggle-style evaluation.

Key file: `taxi-rider-retention.ipynb`

### [Spam Classification](spam-classification/)
Text classification pipeline to distinguish spam from legitimate messages. Implemented TF-IDF vectorization and logistic regression; evaluated with precision, recall, and F1 metrics.

Key file: `spam-classification.ipynb`  
*Note: training data excluded due to size.*

### [Housing Price Prediction](housing-price-prediction/)
Regression analysis on Cook County (Chicago) property assessments. Feature engineering on location, size, and condition variables; model selection via cross-validation; residual diagnostics.

Key file: `housing-price-prediction.ipynb`  
*Note: training data excluded due to size (~94 MB).*

### [Food Safety EDA](food-safety-eda/)
Exploratory analysis of San Francisco restaurant health inspection records. Joined multiple tables (businesses, inspections, violations) to surface risk patterns by neighborhood and cuisine type.

Key files: `food-safety-eda.ipynb`, `data/`

### [Twitter Sentiment Analysis](twitter-text-analysis/)
NLP pipeline on Twitter data using VADER sentiment scoring and regex-based feature extraction. Analyzed sentiment trends across topics and user demographics.

Key file: `twitter-text-analysis.ipynb`  
*Note: Twitter corpus excluded due to size (~79 MB).*

### [Bike Sharing Visualization](bike-sharing-visualization/)
Data visualization study on Capital Bikeshare ridership. Explored diurnal patterns, seasonal effects, and casual vs. registered rider behavior using Seaborn and Matplotlib.

Key files: `bike-sharing-visualization.ipynb`, `data/`, `images/`

### [IMDB SQL Queries](imdb-sql/)
Relational database querying on a structured IMDB mini-dataset. Wrote multi-table JOIN, GROUP BY, and window function queries to answer analytical questions about movies, actors, and ratings.

Key files: `imdb-sql.ipynb`, `data/imdbmini.db`

### [Sklearn Pipeline](sklearn-pipeline/)
Feature preprocessing and model selection using scikit-learn pipelines. Demonstrated ColumnTransformer, StandardScaler, OneHotEncoder, and GridSearchCV on a tabular classification task.

Key file: `sklearn-pipeline.ipynb`

### [Logistic Regression](logistic-regression/)
From-scratch and sklearn logistic regression with precision-recall analysis. Explored decision thresholds, ROC curves, and class imbalance handling.

Key file: `logistic-regression.ipynb`

---

## Tech Stack

- **Python** — pandas, NumPy, scikit-learn, matplotlib, seaborn
- **SQL** — SQLite via Python's `sqlite3`
- **NLP** — VADER sentiment, regex, TF-IDF
