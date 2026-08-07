# 🎓 Smart Face Recognition Attendance System using Machine Learning

> A real-time facial recognition attendance system developed using **Machine Learning**, **Computer Vision**, and **Flask** that automatically identifies students and records attendance.

<p align="center">

![Python](https://img.shields.io/badge/Python-3.11-blue?logo=python)
![Flask](https://img.shields.io/badge/Flask-Web%20Framework-black?logo=flask)
![OpenCV](https://img.shields.io/badge/OpenCV-Computer%20Vision-green?logo=opencv)
![MediaPipe](https://img.shields.io/badge/MediaPipe-Face%20Detection-orange)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-Random%20Forest-red?logo=scikitlearn)
![SQLite](https://img.shields.io/badge/SQLite-Database-blue?logo=sqlite)
![License](https://img.shields.io/badge/License-MIT-yellow)

</p>

---

# 📖 Project Overview

Traditional attendance systems consume valuable classroom time and are prone to manual errors and proxy attendance.

This project automates the entire attendance process using **Machine Learning** and **Computer Vision**.

The system detects a student's face, extracts facial features using **Histogram of Oriented Gradients (HOG)**, classifies the face using a **Random Forest Classifier**, and automatically records attendance in a SQLite database.

---

# ✨ Features

- 👤 Student Registration
- 📷 Automatic Face Dataset Collection
- 🤖 Random Forest Model Training
- 🧠 HOG Feature Extraction
- 🎥 Real-Time Face Recognition
- ✅ Automatic Attendance Marking
- 🚫 Duplicate Attendance Prevention
- 🗄 SQLite Database Integration
- 📄 Attendance Report Download (CSV)
- 🌐 Flask Web Application

---

# 🛠 Technology Stack

| Category | Technology |
|-----------|------------|
| Programming Language | Python |
| Backend | Flask |
| Frontend | HTML, CSS, JavaScript |
| Database | SQLite |
| Face Detection | MediaPipe |
| Feature Extraction | Histogram of Oriented Gradients (HOG) |
| Machine Learning | Random Forest Classifier |
| Image Processing | OpenCV |
| ML Library | Scikit-Learn |

---

# 🧠 Machine Learning Pipeline

```text
Camera
      │
      ▼
MediaPipe Face Detection
      │
      ▼
Face Cropping
      │
      ▼
Histogram Equalization
      │
      ▼
Gaussian Blur
      │
      ▼
Resize Image
      │
      ▼
HOG Feature Extraction
      │
      ▼
Random Forest Classifier
      │
      ▼
Student Identification
      │
      ▼
Attendance Validation
      │
      ▼
Duplicate Attendance Check
      │
      ▼
SQLite Database
```

---

# 📂 Project Structure

```text
Smart-Face-Recognition-Attendance-System
│
├── app.py
├── model.py
├── requirements.txt
├── README.md
├── .gitignore
├── static/
├── templates/
├── dataset/
├── uploads/
├── train_status.json
└── model.pkl
```

---

# 🚀 Installation

Clone the repository

```bash
git clone https://github.com/YOUR_USERNAME/Smart-Face-Recognition-Attendance-System.git
```

Go inside the project

```bash
cd Smart-Face-Recognition-Attendance-System
```

Create a virtual environment

```bash
python -m venv venv
```

Activate the environment

### Windows

```bash
venv\Scripts\activate
```

### Linux / macOS

```bash
source venv/bin/activate
```

Install dependencies

```bash
pip install -r requirements.txt
```

Run the project

```bash
python app.py
```

---

# 📷 Application Workflow

### 1️⃣ Register Student

Capture multiple face images for every student.

---

### 2️⃣ Train Model

Generate facial feature vectors using HOG and train the Random Forest classifier.

---

### 3️⃣ Real-Time Recognition

Recognize students through the webcam.

---

### 4️⃣ Attendance Recording

Attendance is automatically stored in SQLite.

---

# 📸 Screenshots

## Home Page

> *(Add Screenshot Here)*

---

## Student Registration

> *(Add Screenshot Here)*

---

## Model Training

> *(Add Screenshot Here)*

---

## Live Recognition

> *(Add Screenshot Here)*

---

## Attendance Records

> *(Add Screenshot Here)*

---

# 🌍 Sustainable Development Goals (SDGs)

This project contributes towards:

### 🎓 SDG 4 – Quality Education

- Automates attendance
- Saves classroom time
- Improves educational efficiency

### 💡 SDG 9 – Industry, Innovation and Infrastructure

- Uses Artificial Intelligence
- Machine Learning
- Computer Vision

### 🛡 SDG 16 – Peace, Justice and Strong Institutions

- Prevents proxy attendance
- Maintains transparent attendance records

---

# 🔮 Future Scope

- Deep Learning based Recognition
- FaceNet Integration
- Mobile Application
- Cloud Database
- Face Anti-Spoofing
- Liveness Detection
- Multi-Camera Support
- ERP Integration
- Student Dashboard

---

# 👨‍💻 Contributors

### Prathamesh Suraj

- PRN: 124BTCM1191

---

### Neha Raparti

- PRN: 124BTCM1061

---

# 📜 License

This project is developed for educational and academic purposes.

---

# ⭐ If you like this project

Please consider giving it a ⭐ on GitHub.