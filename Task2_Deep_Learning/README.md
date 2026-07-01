# 🚀 Task 2 – Deep Learning Image Classification using PyTorch

## 📌 Overview

This project was completed as **Task 2** of my **AI & Machine Learning Internship at Alfido Tech**.

The objective of this project is to classify images into different categories using a Deep Learning model. I implemented **Transfer Learning** with **ResNet18** to build an accurate image classification system on the **CIFAR-10** dataset.

---

## 🎯 Objectives

* Build an image classification model using Deep Learning.
* Apply Transfer Learning with ResNet18.
* Perform image preprocessing and augmentation.
* Train and evaluate the model.
* Save the trained model for deployment.

---

## 📂 Dataset

* **Dataset:** CIFAR-10
* **Total Training Images:** 50,000
* **Total Testing Images:** 10,000
* **Classes:** 10

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

## 🛠️ Technologies Used

* Python
* PyTorch
* TorchVision
* NumPy
* Matplotlib
* PIL (Pillow)
* Jupyter Notebook
* VS Code

---

## ⚙️ Project Workflow

1. Dataset Loading
2. Image Preprocessing
3. Data Augmentation
4. Transfer Learning (ResNet18)
5. Model Training
6. Loss Calculation
7. Model Evaluation
8. Model Saving

---

## 🧠 Deep Learning Model

**Model Used:** ResNet18 (Transfer Learning)

* Pre-trained ResNet18 architecture
* Modified final fully connected layer for 10 CIFAR-10 classes
* Optimized using CrossEntropyLoss and Adam Optimizer

---

## 📊 Results

| Metric        | Value      |
| ------------- | ---------- |
| Training Loss | **0.3961** |
| Test Accuracy | **75.50%** |

---

## 📁 Project Structure

```text
Task2_Deep_Learning/
│
├── notebook.ipynb
├── dataset/
├── models/
│   └── cifar10_resnet18.pth
├── requirements.txt
└── README.md
```

---

## ▶️ How to Run

```bash
pip install -r requirements.txt
```

Open the Jupyter Notebook and run all cells sequentially.

---

## 📚 Learning Outcomes

Through this project, I gained practical experience in:

* Deep Learning
* Transfer Learning
* Computer Vision
* Image Classification
* PyTorch
* Model Evaluation
* Model Saving and Reusability

---

## 🚀 Future Improvements

* Increase model accuracy using advanced data augmentation.
* Experiment with EfficientNet and Vision Transformers.
* Deploy the trained model as a web application.
* Train on larger image datasets.

---

## 👨‍💻 Author

**Amit**

B.Tech (Artificial Intelligence)

GitHub: https://github.com/amit86852005-stack

LinkedIn: https://www.linkedin.com/in/amit-aa5086295/
