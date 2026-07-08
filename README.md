# 🧠 Parkinson Disease Detection Using Machine Learning

A Machine Learning-powered web application that detects **Parkinson's Disease** from voice recordings by analyzing speech features. The project leverages machine learning algorithms to assist in the early diagnosis of Parkinson's disease through an easy-to-use Flask web interface.

---

## 📖 Table of Contents

- Introduction
- Features
- Technologies Used
- Project Structure
- Installation
- Usage
- Machine Learning Model
- Future Improvements
- Contributing
- License

---

## 📌 Introduction

Parkinson's Disease is a progressive neurological disorder that primarily affects movement and speech. Early diagnosis can significantly improve treatment and disease management.

This project uses **Machine Learning** to analyze voice recordings and predict whether a person is likely to have Parkinson's disease. The application extracts important voice features, processes them using a trained machine learning model, and displays the prediction through a user-friendly web interface.

---

## ✨ Features

- 🎤 Voice-based Parkinson's disease prediction
- 🤖 Machine Learning classification model
- 🌐 User-friendly Flask web application
- 📊 Automatic voice feature extraction
- ⚡ Fast and accurate prediction
- 📁 Audio file upload support (.wav/.mp3)
- 📱 Simple and responsive interface

---

## 🛠 Technologies Used

### Programming Language
- Python

### Machine Learning
- Scikit-learn
- Support Vector Machine (SVM)

### Libraries
- Pandas
- NumPy
- Librosa
- Parselmouth (Praat)
- Pickle

### Web Framework
- Flask

### Frontend
- HTML5
- CSS3
- JavaScript

### Development Tools
- Visual Studio Code
- Jupyter Notebook
- Git
- GitHub

---

## 📂 Project Structure

```
ParkinsonDiseaseDetection/
│
├── application.py          # Flask Application
├── Parkinson_disease.pkl   # Trained ML Model
├── templates/              # HTML Pages
├── static/                 # CSS & JavaScript
├── uploads/                # Uploaded Audio Files
├── requirements.txt
├── README.md
└── dataset/
```

---

## ⚙️ Installation

### 1. Clone the Repository

```bash
git clone https://github.com/NisargDetroja1/ParkinsonDiseaseDetection.git
```

### 2. Navigate to the Project Folder

```bash
cd ParkinsonDiseaseDetection
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

### 4. Run the Application

```bash
python application.py
```

### 5. Open Your Browser

```
http://127.0.0.1:5000
```

---

## 🚀 Usage

1. Launch the Flask application.
2. Upload a voice recording (.wav or .mp3).
3. The system extracts speech features automatically.
4. The trained Machine Learning model analyzes the input.
5. The application predicts whether Parkinson's Disease is detected.

---

## 🤖 Machine Learning Model

The project uses a **Support Vector Machine (SVM)** classifier trained on Parkinson's voice datasets.

### Voice Features Extracted

- Fundamental Frequency (Fo)
- Maximum Frequency
- Minimum Frequency
- Jitter
- Shimmer
- Harmonic-to-Noise Ratio (HNR)
- RPDE
- DFA
- PPE
- Additional speech biomarkers

The trained model is serialized using **Pickle** for efficient deployment in the Flask application.

---

## 📈 Future Improvements

- Deep Learning-based prediction
- Higher prediction accuracy
- User authentication
- Cloud deployment
- Mobile application
- Medical report generation
- Prediction history
- Real-time voice recording support

---

## 🎯 Learning Outcomes

- Machine Learning Model Development
- Voice Signal Processing
- Speech Feature Extraction
- Flask Web Development
- Model Deployment
- Healthcare AI Applications

---

## 🤝 Contributing

Contributions are welcome!

1. Fork the repository
2. Create a new feature branch
3. Commit your changes
4. Push to your branch
5. Open a Pull Request

---

## 👨‍💻 Author

**Nisarg Detroja**

B.Tech Computer Engineering Student

GitHub: https://github.com/NisargDetroja1

---

## 📄 License

This project is developed for educational and research purposes.

Licensed under the MIT License.
