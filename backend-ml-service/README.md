# Car Marketplace - Loan Prediction Service

Flask API providing real-time loan eligibility predictions using machine learning for instant loan approval decisions.

## 🎯 Overview

ML microservice delivering instant loan approval decisions with trained RandomForest model achieving **80% accuracy and 97% recall** - optimized for loan approval business requirements.

## 🧠 Machine Learning

### **Model Performance**
- **Algorithm**: RandomForest Classifier
- **Accuracy**: 80%
- **Recall**: 97% (optimized for business case)
- **Features**: 9 financial and demographic inputs
- **Training**: Systematic comparison of 6 algorithms with hyperparameter tuning

### **Production ML Pipeline**
- **Data preprocessing**: Normalization, encoding, missing value handling
- **Feature engineering**: Correlation-based selection
- **Model persistence**: Pickle serialization for production serving
- **Real-time inference**: Sub-second prediction response

## 🚀 Key Features

- **Instant loan decisions** integrated into purchase workflow
- **Credit score calculation** (0-1 scale)
- **Comprehensive input validation** and error handling
- **Production API** with CORS support for frontend integration

## 🛠️ Tech Stack

- **Framework**: Flask with production WSGI support
- **ML Stack**: scikit-learn, pandas, numpy
- **Model**: RandomForest with optimized hyperparameters
- **Deployment**: Production-ready configuration

## 📡 API Endpoint

- `POST /predict_loan_eligibility`
  - **Input**: Applicant financial profile
  - **Output**: Loan eligibility + credit score
  - **Performance**: <500ms response time

## 🔬 ML Development

Complete data science pipeline: EDA → Preprocessing → Model Selection → Hyperparameter Tuning → Cross-validation → Production Deployment

## 🎓 Technical Achievement

End-to-end ML engineering from model development to production API deployment. Demonstrates real-world ML integration with business workflows. Built as part of comprehensive 7-month marketplace development showcasing production ML systems.
