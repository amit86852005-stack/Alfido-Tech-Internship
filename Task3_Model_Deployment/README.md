# 🚀 Task 3 – Image Classification Model Deployment using FastAPI & Docker

## 📌 Overview

This project was completed as **Task 3** of my **AI & Machine Learning Internship at Alfido Tech**.

The objective of this task was to deploy the trained **ResNet18 Image Classification Model** as a REST API using **FastAPI** and containerize the application using **Docker**.

The API accepts an uploaded image, preprocesses it, performs inference using the trained deep learning model, and returns the predicted class in JSON format.

---

## 🎯 Objectives

* Deploy a trained PyTorch model.
* Build REST APIs using FastAPI.
* Upload images through API.
* Perform real-time image classification.
* Return predictions in JSON format.
* Containerize the application using Docker.

---

## 📂 Project Features

* Image Upload API
* Real-Time Prediction
* FastAPI REST API
* Interactive Swagger Documentation
* Docker Support
* JSON Response
* PyTorch Model Deployment

---

## 🛠️ Technologies Used

* Python
* FastAPI
* PyTorch
* TorchVision
* Pillow (PIL)
* Uvicorn
* Docker

---

## ⚙️ Project Workflow

1. Load Trained ResNet18 Model
2. Start FastAPI Server
3. Upload Image
4. Image Preprocessing
5. Model Inference
6. Return Prediction
7. Docker Container Deployment

---

## 🧠 Deep Learning Model

* Model: ResNet18
* Framework: PyTorch
* Dataset: CIFAR-10
* Number of Classes: 10

Classes:

* Airplane
* Automobile
* Bird
* Cat
* Deer
* Dog
* Frog
* Horse
* Ship
* Truck

---

## 📁 Project Structure

```text
Task3_Model_Deployment/
│
├── app.py
├── Dockerfile
├── requirements.txt
├── models/
│   └── cifar10_resnet18.pth
└── README.md
```

---

## ▶️ Run Locally

Install dependencies:

```bash
pip install -r requirements.txt
```

Start the API server:

```bash
uvicorn app:app --reload
```

Open Swagger UI:

```text
http://127.0.0.1:8000/docs
```

---

## 🐳 Docker

Build Docker Image:

```bash
docker build -t image-classification-api .
```

Run Docker Container:

```bash
docker run -p 8000:8000 image-classification-api
```

---

## 📌 API Endpoint

### POST `/predict`

Upload an image and receive the predicted class.

### Example Response

```json
{
  "filename": "image.png",
  "prediction": "ship",
  "status": "Success"
}
```

---

## 📚 Learning Outcomes

Through this project, I gained practical experience in:

* Model Deployment
* REST API Development
* FastAPI
* Docker Containerization
* Image Processing
* Production-ready AI Applications

---

## 🚀 Future Improvements

* Deploy on Render or Railway
* Add confidence score
* Support batch predictions
* Improve UI with Streamlit or React
* Deploy on cloud platforms

---

## 👨‍💻 Author

**Amit**

B.Tech (Artificial Intelligence)

GitHub: https://github.com/amit86852005-stack

LinkedIn: https://www.linkedin.com/in/amit-aa5086295/
