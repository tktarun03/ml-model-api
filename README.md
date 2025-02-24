# ml-model-api

A simple Flask API to serve a machine learning model for predictions.

## 🚀 Features
- A **Flask API** that serves a trained machine learning model.
- Accepts **JSON input** and returns **predictions**.
- Lightweight and easy to deploy.

## 📂 Project Structure
```
ml-model-api/
│── src/
│   ├── app.py  # Flask API for serving predictions
│── requirements.txt  # Dependencies
│── README.md
```

## 🛠 Installation & Usage

1. Clone the repository:
   ```bash
   git clone https://github.com/tktarun03/ml-model-api.git
   cd ml-model-api
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Start the Flask API server:
   ```bash
   python src/app.py
   ```

4. Send a **POST request** to `http://127.0.0.1:5000/predict` with JSON data:

   ```bash
   curl -X POST http://127.0.0.1:5000/predict -H "Content-Type: application/json" -d '{ "features": [5.1, 3.5, 1.4, 0.2] }'
   ```

5. The API will return a **prediction response**.

## 👨‍💻 About the Author

🚀 Created by [Arunkumar Thamilarasu](https://github.com/tktarun03) | UI Technical Architect | Machine Learning & Flask Expert

## ⭐ Contribute & Support
- Fork & Star this repository! ⭐
- Submit Issues and PRs to improve the API.

---
🎯 **Follow me on GitHub**: [@tktarun03](https://github.com/tktarun03)
