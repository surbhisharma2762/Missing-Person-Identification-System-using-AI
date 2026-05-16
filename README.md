# Missing Person Identification System using AI
Smart AI system for missing person identification using face recognition and machine learning
# 🚀 Missing Person Identification System

AI-powered missing person identification system using facial recognition, computer vision and machine learning.

![Python](https://img.shields.io/badge/Python-3.10-blue)
![Streamlit](https://img.shields.io/badge/Streamlit-WebApp-red)
![MediaPipe](https://img.shields.io/badge/MediaPipe-FaceMesh-green)
![OpenCV](https://img.shields.io/badge/OpenCV-ImageProcessing-orange)
![SQLite](https://img.shields.io/badge/SQLite-Database-lightgrey)
![License](https://img.shields.io/badge/License-MIT-yellow)

---

# 📌 Overview

This project helps identify missing persons using AI based facial recognition.

The system allows:

* Officers to register missing person cases
* Public users to submit sightings
* AI to automatically match faces
* Admins to monitor cases using dashboards and maps

The project uses:

* MediaPipe Face Mesh
* OpenCV
* KNN Machine Learning
* Streamlit
* SQLite Database

---

# ✨ Features

✅ Face Detection using AI
✅ Facial Landmark Extraction (468 Points)
✅ Image & Video Upload Support
✅ KNN Face Matching
✅ Public Sighting Portal
✅ Interactive Dashboard
✅ India Case Map Visualization
✅ Role Based Login System
✅ Email Notifications
✅ SQLite Database Integration

---

# 🧠 Technologies Used

| Technology   | Purpose                              |
| ------------ | ------------------------------------ |
| Python       | Main programming language            |
| Streamlit    | Frontend web application             |
| MediaPipe    | Face detection & landmark extraction |
| OpenCV       | Image/video processing               |
| scikit learn | KNN face matching                    |
| SQLite       | Database                             |
| Folium       | Interactive maps                     |
| bcrypt       | Password hashing/security            |

---

# 📂 Project Structure

```bash
Finding-missing-person-using-AI/
│
├── Home.py                     # Main dashboard
├── mobile_app.py               # Public submission portal
├── login_config.yml            # User authentication
├── requirements.txt
│
├── pages/
│   ├── 1_Register New Case.py
│   ├── 2_All Cases.py
│   ├── 3_Match Cases.py
│   ├── 4_Help.py
│   └── 5_Map.py
│
├── helper/                     # Backend helper functions
├── resources/                  # Uploaded images/videos
├── scripts/                    # Demo data scripts
└── sqlite_database.db          # SQLite database
```

---

# ⚙️ Installation

## Clone Repository

```bash
git clone https://github.com/your-username/Finding-missing-person-using-AI.git
cd Finding missing person using AI
```

---

## Create Virtual Environment

### Windows

```bash
python -m venv venv
venv\Scripts\activate
```

### Linux/Mac

```bash
python3 -m venv venv
source venv/bin/activate
```

---

## Install Requirements

```bash
pip install -r requirements.txt
```

---

# ▶️ Run the Application

## Admin/Officer Portal

```bash
streamlit run Home.py
```

## Public Submission Portal

```bash
streamlit run mobile_app.py
```

---

# 🔐 Login Credentials

Add users inside:

```bash
login_config.yml
```

---

# 🖼️ Where Image Processing is Used

| Feature                  | Technology | File Location            |
| ------------------------ | ---------- | ------------------------ |
| Face Detection           | MediaPipe  | `helper/`                |
| Face Landmark Extraction | MediaPipe  | `1_Register New Case.py` |
| Video Frame Processing   | OpenCV     | `3_Match Cases.py`       |
| Face Matching            | KNN        | `3_Match Cases.py`       |
| Map Visualization        | Folium     | `5_Map.py`               |

---

# 🧠 AI Workflow

```text
Image Upload
     ↓
Face Detection (MediaPipe)
     ↓
468 Landmark Extraction
     ↓
Face Vector Creation
     ↓
KNN Face Matching
     ↓
Result Stored in SQLite
     ↓
Dashboard Visualization
```

---

# 📊 Future Improvements

* Deep Learning Face Embeddings
* Mobile Application
* Real Time CCTV Integration
* Cloud Database
* Multi language Support
* Advanced Analytics Dashboard

---

# 🤝 Contributing

Contributions are welcome!

## Steps to Contribute

1. Fork the repository
2. Create a new branch
3. Make changes
4. Commit your changes
5. Push to your fork
6. Create a Pull Request

