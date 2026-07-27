# Um E Kulsoom

Final-year BS AI student building end-to-end ML and data pipelines — ingestion, training, experiment tracking, and deployment.

BS Artificial Intelligence, FAST-NUCES (Expected 2027)
AWS Cloud Practitioner (DataCamp) · Associate Data Scientist in Python (DataCamp) · GitHub Foundations
[LinkedIn](https://linkedin.com/in/um-e-kulsoom) · [Mail](kulsoomume362@gmail.com)

---

## Featured Projects

**[Real-Time Streaming Data Pipeline](https://github.com/KayTheCoder-101/Real-Time-Streaming-Data-Pipeline)**
Solo-built pipeline ingesting live BTC/USDT trades from the Binance WebSocket API through Kafka into Spark Structured Streaming, landing raw and 1-minute OHLC-aggregated data as Parquet in a MinIO data lake, served through Spark Thrift Server to live Superset dashboards. Airflow orchestrates scheduled Parquet compaction. Diagnosed and resolved a race condition where batch compaction could corrupt Structured Streaming's exactly-once metadata log.
`Kafka` `Spark Structured Streaming` `MinIO` `Airflow` `Superset` `Docker`

**[Log Analysis Dashboard with Anomaly Detection](https://github.com/KayTheCoder-101/log-anomaly-dashboard)**
End-to-end system generating, ingesting, and analyzing application logs in real time. A FastAPI ingestion service backed by PostgreSQL feeds an Isolation Forest model that flags anomalies — traffic spikes, server errors, suspicious IP activity — on a live Streamlit dashboard. Containerized with Docker Compose, validated with GitHub Actions CI.
`FastAPI` `PostgreSQL` `scikit-learn` `Streamlit` `Docker` `GitHub Actions`

**[Real-Time Market Movement Prediction](https://github.com/KayTheCoder-101/market-sentiment-prediction-mlops)**
End-to-end pipeline ingesting live data from Yahoo Finance, Reuters, Reddit, and Twitter to predict market direction and volatility using RNN, LSTM, and GRU models. Full MLOps stack — DVC, MLflow, Airflow, GitHub Actions CI/CD — with a FastAPI REST API deployed on AWS EC2 via Docker.
`RNN/LSTM/GRU` `DVC` `MLflow` `Airflow` `AWS EC2`

**[Automatic Headline Generator (NLP)](https://github.com/KayTheCoder-101/headline-generation-nlp)**
Designed and benchmarked three architectures — Seq2Seq BiLSTM with Bahdanau Attention, BART, and a custom T5 with Hybrid Attention — on the CNN/DailyMail dataset. The custom T5+Hybrid model reached 91% of BART's performance with 45% fewer parameters (62M vs. 139M).
`Seq2Seq` `BART` `T5` `ROUGE`

**[Pakistani Politician Image Classification](https://github.com/KayTheCoder-101/pakistani-politician-cnn-classifier)**
Multi-class facial recognition system classifying 16 public figures on 1,280+ images, with ResNet-50 and EfficientNet fine-tuned to 90%+ accuracy. Dataset versioned with DVC, experiments tracked via MLflow, deployed on AWS EC2.
`CNN` `ResNet-50` `EfficientNet` `DVC` `MLflow` `AWS`

---

## Tech Stack

**Languages:** Python · SQL · C++ · C# · JavaScript
**ML / Data:** scikit-learn · pandas · NumPy · NLP · Computer Vision
**MLOps & Infrastructure:** Docker · AWS · MLflow · DVC · Airflow · Kafka · Spark · CI/CD
**Databases & BI:** PostgreSQL · MySQL · SQL Server · Power BI · Tableau

---

Open to entry-level roles in AI/ML engineering, data engineering, and data science.
