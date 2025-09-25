# Heart Disease Prediction - MLOps Pipeline

An end-to-end machine learning pipeline for heart disease prediction with fairness considerations, built using modern DataOps and MLOps practices.

## 🎯 Project Overview

This project demonstrates production-ready ML engineering by building a comprehensive pipeline that:
- Predicts heart disease from patient data (UCI Heart Disease dataset)
- Implements fairness evaluation and bias mitigation
- Uses modern data engineering tools (Spark, Delta Lake, Airflow)
- Follows MLOps best practices (MLflow, Docker, Kubernetes, CI/CD)

## 🏗️ Architecture

**Hybrid Databricks + Kubernetes Architecture:**
- **Data Engineering Layer (Databricks):** Spark ETL, Delta Lake, feature engineering, model training
- **Model Serving Layer (Kubernetes):** FastAPI deployment, monitoring, DevOps practices

## ✅ Current Progress

- [x] Project setup and Git repository
- [x] Python environment with core dependencies
- [x] UCI Heart Disease dataset downloaded and cleaned (297 records)
- [x] Initial data exploration and type conversion
- [ ] Synthetic data generation (scale to 100K+ rows)
- [ ] Feature engineering pipeline
- [ ] Model training with MLflow tracking
- [ ] Fairness evaluation and bias mitigation
- [ ] Docker containerization and Kubernetes deployment
- [ ] CI/CD pipeline setup
- [ ] Monitoring and observability

## 📊 Dataset

**UCI Heart Disease Dataset (297 patients)**
- 13 features: age, sex, chest pain, blood pressure, cholesterol, etc.
- Target: presence of heart disease (0-4 scale)
- Sensitive attributes: age, sex (for fairness analysis)

## 🛠️ Technology Stack

**Data Engineering:** PySpark, Delta Lake, Apache Airflow <br/>
**ML/MLOps:** Scikit-learn, MLflow, Fairlearn <br/>
**Deployment:** Docker, Kubernetes, FastAPI <br/>
**Cloud:** Databricks, AWS/Azure (planned) <br/>
**CI/CD:** GitHub Actions

## 🚀 Getting Started

```bash
# Clone repository
git clone https://github.com/yourusername/heart-disease-mlops.git
cd heart-disease-mlops

# Set up environment
python -m venv venv
source venv/bin/activate  # Windows: venv\Scripts\activate
pip install -r requirements.txt

# Explore data
jupyter lab
```

## 📈 Planned Features

- **Fairness-First ML:** Demographic parity, equalized odds evaluation
- **Production Scale:** Synthetic data generation for realistic testing
- **Real-time Streaming:** Kafka + Spark Structured Streaming
- **Monitoring:** Prometheus, Grafana, data drift detection
- **Infrastructure as Code:** Terraform for cloud resources

---
*An end-to-end MLOps pipeline focused on ethical AI and production best practices*
