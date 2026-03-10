## 🚀 Live Demo

API Documentation:
https://network-security-xraj.onrender.com/docs

Upload a CSV file to the `/predict` endpoint to detect phishing websites.

## Tech Stack
- Python
- FastAPI
- Scikit-learn
- Docker
- GitHub Actions (CI/CD)
- Render (Deployment)
- MongoDB Atlas
- MLflow + DagsHub


User
   ↓
FastAPI API
   ↓
Preprocessor (preprocessor.pkl)
   ↓
ML Model (model.pkl)
   ↓
Prediction
   ↓
HTML Table Output
