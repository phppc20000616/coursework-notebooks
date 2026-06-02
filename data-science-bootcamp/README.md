# Data Science Bootcamp — Python

Projects from a data science intensive program, covering Python fundamentals, data wrangling, API integration, SQL analytics, machine learning, and consumer behavior modeling.

---

## Projects

### [Python Fundamentals](python-fundamentals/)
Introduction to Python for data science: data types, control flow, functions, list comprehensions, and NumPy/pandas basics. Available as both a Jupyter notebook and a standalone Python script.

Key files: `python-fundamentals.ipynb`, `python-fundamentals.py`

### [Job Market Analysis](job-market-analysis/)
Exploratory data analysis on a large-scale job postings dataset. Examined hiring trends by industry, identified in-demand skills, and visualized the distribution of roles across sectors using pandas and matplotlib.

Key files: `job-market-analysis.ipynb`, `industries.csv`, `job_industries.csv`  
*Note: full job postings dataset excluded due to size (~129 MB).*

### [API Data Collection](api-data-collection/)
End-to-end data pipeline using public REST APIs. Fetched live flight price data from the Kayak Explore API, parsed JSON responses, and performed exploratory analysis on pricing patterns across destinations.

Key file: `api-data-collection.ipynb`

### [Stock & Social Analytics](stock-social-analytics/)
SQL-based analysis of NVIDIA stock price data combined with OpenAI website traffic metrics. Wrote multi-step queries to surface correlations between social interest and stock movement over time.

Key files: `stock-social-analytics.ipynb`, `nvda.db`, `openai_visits.csv`

### [Classification Models](classification-models/)
Two applied classification tasks in one project:
- **Restaurant Success Prediction** — collected Yelp feature data (price tier, delivery, seating) and trained a classifier to predict shop viability
- **Spam Email Detection** — applied Support Vector Machine (SVM) on pre-extracted TF-IDF document-term matrices to classify spam vs. legitimate email at varying training set sizes

Key files: `classification-models.ipynb`, `Italian Restaurant Data Template.xlsx`, `MATRIX.*`

### [Consumer Behavior Classification](consumer-behavior-classification/)
Binary classification on iPhone purchase records. Engineered features from demographic and salary data; trained and evaluated logistic regression and decision tree classifiers using scikit-learn pipelines with cross-validation.

Key files: `consumer-behavior-classification.ipynb`, `iphone_purchase_records.csv`

---

## Tech Stack

- **Python** — pandas, NumPy, scikit-learn, matplotlib
- **SQL** — SQLite via Python's `sqlite3`
- **APIs** — REST/JSON with `requests`
