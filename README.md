# 🎓 Student Performance API & Analysis

A complete end-to-end project demonstrating:

* 📊 Data Analysis & Visualization  
* 🤖 Machine Learning Prediction  
* 🚀 FastAPI Backend (CRUD API)  
* 🧪 Automated Testing (Pytest)  
* 🐳 Docker Containerization  

---

## 📌 Project Overview

This system helps analyze and manage student performance by:

* Analyzing scores across different courses
* Visualizing trends and averages
* Predicting scores using Machine Learning
* Providing a REST API for student management
* Running tests for reliability
* Deploying via Docker

---

## 📊 Data Analysis Output

### ✅ Average Scores by Course

CSE  → 60.66  
ECE  → 83.00  
IT   → 68.00  

### ✅ Probability of Passing

Probability of Passing: 1.0 (100%)

---

## 📈 Visualizations

### 📊 Average Scores Bar Chart

![Bar Chart](Bar_Chart.png)

### 📉 Score Trend Visualization

![Score Trend](Line_Chart.png)

---

## 🤖 Machine Learning Output

![ML Output](ML.png)

### 📌 Model Results

RMSE: 2.37  
Predicted score for 5 hours study: 74.0  

---

## 🚀 FastAPI Backend

### ▶️ Run Server

```bash
python -m uvicorn main:app --reload
```

### 🌐 API Base URL

http://127.0.0.1:8000

---

### 📌 Available Endpoints

| Method | Endpoint             | Description       |
|--------|----------------------|------------------|
| GET    | /docs                | Swagger UI        |
| POST   | /students            | Add student       |
| GET    | /students            | Get all students  |
| GET    | /students/{id}       | Get student by ID |
| PUT    | /students/{id}       | Update student    |
| DELETE | /students/{id}       | Delete student    |
| GET    | /students?course=CSE | Filter by course  |

---

### 🧪 API Logs Example

![FastAPI Logs](FastAPI.png)

---

## 🧪 Testing (Pytest)

![Pytest Results](Pytest.png)

### ✅ Test Summary

1 passed in 0.86s

### ▶️ Run Tests

```bash
pytest -v
```

---

## 🐳 Dockerization

### ▶️ Build Docker Image

```bash
docker build -t student-api .
```

### ▶️ Run Container

```bash
docker run -d -p 8000:8000 student-api
```

---

### 📦 Docker Images

![Docker Images](Dockerization.png)

### 📦 Running Containers

![Docker Containers](Dockerization_2.png)

---

## 🛠️ Tech Stack

* Python  
* Pandas  
* Matplotlib  
* Scikit-learn  
* FastAPI  
* Uvicorn  
* Pytest  
* Docker  

---

## 📂 Project Structure

.
├── main.py  
├── analysis.py  
├── ml.py  
├── test_main.py  
├── requirements.txt  
├── Dockerfile  
├── Bar_Chart.png  
├── Line_Chart.png  
├── ML.png  
├── Pytest.png  
├── FastAPI.png  
├── Dockerization.png  
├── Dockerization_2.png  
└── README.md  

---

## ⚡ Key Highlights

* 📊 Automated data analysis pipeline  
* 📉 Visualization of trends and averages  
* 🤖 ML-based prediction system  
* 🚀 RESTful API with CRUD operations  
* 🧪 Tested with Pytest  
* 🐳 Fully Dockerized application  
* 📦 Clean and modular structure  

---

## 📬 Future Improvements

* 🔐 Add authentication (JWT)
* 🗄️ Integrate database (PostgreSQL / MongoDB)
* ☁️ Deploy to cloud (AWS / Azure / GCP)
* 💻 Build frontend dashboard (React)
* 📈 Add advanced ML models

---

## 👨‍💻 Author

Kushagra

---

## ⭐ Support

If you found this project useful:

⭐ Star the repo  
🍴 Fork it  
📢 Share it  
