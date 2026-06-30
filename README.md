# Sanjo Joy

**Applied Machine Learning · Experimentation & Causal Inference · Data & Research Engineering**

Data scientist based in Berlin with 4+ years applying machine learning, statistical
experimentation, and large-scale data analysis to consumer-marketplace problems at
Amazon (EU/NA). MSc in Business Analytics and Data Science (IE University, Madrid).
I like problems that need both rigorous modelling and reproducible engineering to ship.

📍 Berlin, Germany &nbsp;·&nbsp; 🔗 [LinkedIn](https://linkedin.com/in/sanjojoy) &nbsp;·&nbsp; ✉️ sanjojoys@gmail.com

---

## Selected Projects

###  [Nifty 50 Index Forecasting](https://github.com/sanjojoys/nifty-50-predictor) — Ensemble Time-Series Model
ARIMA (ADF + AIC order selection) + Random Forest residual correction + GARCH(1,1) volatility
and prediction intervals. Reports rolling one-step-ahead MAPE (~0.87%) and true multi-step
MAPE (~2.73%) separately for honest evaluation. *Python, statsmodels.*

###  [Real-Time Streaming Analytics & ML](https://github.com/sanjojoys/Real-time-Streaming-Data-Analysis)
End-to-end streaming pipeline: Kafka ingestion → Spark Structured Streaming → HDFS →
Spark ML / XGBoost engagement models → Streamlit dashboard. Fully containerised with
Docker Compose. *Kafka, Spark, HDFS, BigQuery ML.*

###  [Predictive Maintenance for IoT Equipment](https://github.com/sanjojoys/predictive-maintenance-iot)
Feature engineering (rolling stats, FFT features), model benchmarking across Logistic
Regression / Random Forest / XGBoost / LSTM with grid + Bayesian tuning, and SHAP/LIME
explainability. Served via a Dockerised FastAPI. *Python, scikit-learn, FastAPI.*

###  [Reproducible Analytics Engineering Pipeline](https://github.com/sanjojoys/ai-support-analytics-pipeline) — Medallion Architecture
Production-grade Modern Data Stack: Bronze/Silver/Gold layers in Snowflake, four Airflow
DAGs, a custom dbt `generate_schema_name` macro, and generic + singular data-quality tests
with CI via GitHub Actions and SQLFluff. *dbt, Snowflake, Airflow.*

###  [Serverless Sentiment Analysis API](https://github.com/sanjojoys/Serverless_sentiment_analysis)
NLP sentiment service on AWS Lambda + API Gateway + Amazon Comprehend, deployed as
Infrastructure-as-Code with AWS SAM. *Python, AWS serverless.*

---

## Toolbox

**ML & Stats:** Random Forest, XGBoost, LSTM, ARIMA/GARCH, SHAP/LIME, A/B testing, causal design
**Languages:** Python (pandas, scikit-learn, statsmodels), SQL, R
**Data & ML Eng:** dbt, Airflow, Spark, Kafka, Docker, FastAPI, CI/CD (GitHub Actions, SQLFluff)
**Platforms:** Snowflake, BigQuery, AWS (Redshift, S3, Lambda), HDFS, PostgreSQL
