# 🏦 FastAPI BankNote Authentication API

This project is a simple yet powerful **Machine Learning API** built with **FastAPI** to authenticate Bank Notes using a pre-trained classification model.

---

## 🚀 Features

- Built with **FastAPI** – high-performance Python web framework.
- **ML Model Integration** using `classifier.pkl` for real-time predictions.
- **CSV Upload** for training and testing data (`BankNote_Authentication.csv`).
- Docker-ready for containerized deployment.
- **Interactive Swagger UI** for testing endpoints.
- Trained using a Jupyter Notebook (`ModelTraining.ipynb`).

---

## 📂 Project Structure

├── app.py # FastAPI app entry point
├── main.py # Alternative main script
├── BankNotes.py # Logic for handling requests and model prediction
├── classifier.pkl # Pre-trained ML model (pickle file)
├── BankNote_Authentication.csv # Dataset
├── ModelTraining.ipynb # Model training notebook
├── requirements.txt # Python dependencies
├── Procfile # Deployment file for Heroku
├── README.md # This file



---yaml

## 🧪 How to Run

### 📌 Install Requirements

```bash
pip install -r requirements.txt

## Run the API

uvicorn app:app --reload

📊 API Endpoints
POST /predict: Submit features and get prediction

GET /: Welcome message or health check

🧠 Model Details
Trained on features like:

Variance

Skewness

Curtosis

Entropy

Algorithms used: Decision Tree / Random Forest (see ModelTraining.ipynb)

Accuracy evaluated and best-performing model serialized into classifier.pkl