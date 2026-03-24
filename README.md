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
<img width="828" height="247" alt="Analysis" src="https://github.com/user-attachments/assets/f3e1ff55-c7a3-45c3-8abf-cf9e0c85970e" />


### ✅ Probability of Passing

Probability of Passing: 1.0 (100%)

---

## 📈 Visualizations

### 📊 Average Scores Bar Chart


<img width="640" height="480" alt="Bar_Chart" src="https://github.com/user-attachments/assets/c58e43e4-eddf-42fc-9ee6-ae77111205a6" />


### 📉 Score Trend Visualization


<img width="640" height="480" alt="Line_Chart" src="https://github.com/user-attachments/assets/01cb5281-c2e3-4de9-9592-082c38e5eef8" />

---

## 🤖 Machine Learning Output


<img width="1135" height="118" alt="ML" src="https://github.com/user-attachments/assets/d601d1ad-8502-43a1-b820-76ea95af6c1d" />


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


<img width="1080" height="467" alt="FastAPI" src="https://github.com/user-attachments/assets/1d9e044d-6d98-490b-9bbe-66c6a1f3e103" />


---

## 🧪 Testing (Pytest)


<img width="1175" height="390" alt="Pytest" src="https://github.com/user-attachments/assets/39312539-d5f3-4b44-a43d-0258d1515cde" />



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


<img width="1307" height="581" alt="Dockerization" src="https://github.com/user-attachments/assets/4a1c188c-99c0-4323-b8b2-11b6c5489c60" />


### 📦 Running Containers


<img width="1382" height="170" alt="Dockerization_2" src="https://github.com/user-attachments/assets/995235de-5d54-451e-89c2-2ed18ac22f60" />


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

## 👨‍💻 Author

Kushagra
