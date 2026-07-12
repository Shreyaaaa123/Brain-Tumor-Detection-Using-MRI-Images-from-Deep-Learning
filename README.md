# 🧠 Brain Tumor Detection using Deep Learning

An AI-powered web application that detects and classifies brain tumors from MRI images using a Convolutional Neural Network (CNN). Built with TensorFlow, Keras, Flask, and OpenCV, the application classifies MRI scans into four categories and provides prediction confidence in real time.

---

## 🚀 Features

- 🧠 Brain MRI classification into 4 classes
- 📤 Upload MRI images through a web interface
- ⚡ Real-time prediction
- 📊 Confidence score for each prediction
- 🖥️ Responsive Flask web application
- 🎯 Deep Learning-based CNN model
- 📁 Clean and modular project structure

---

## 🩺 Tumor Classes

- ✅ No Tumor
- 🔴 Glioma Tumor
- 🟡 Meningioma Tumor
- 🔵 Pituitary Tumor

---

## 🛠️ Tech Stack

### Backend
- Flask
- Python

### Machine Learning
- TensorFlow
- Keras
- OpenCV
- NumPy
- Scikit-learn

### Frontend
- HTML5
- CSS3
- JavaScript

### Tools
- Git
- GitHub
- Kaggle (Model Training)

---

## 📂 Project Structure

```
Brain-Tumor-Detection/
│
├── app.py
├── model/
│   └── brain_tumor.keras
├── static/
│
├── templates/
│   ├── index.html
│   └── result.html
│
├── uploads/
├── requirements.txt
├── README.md
└── .gitignore
```

---

## ⚙️ How It Works

1. User uploads an MRI brain scan.
2. The image is preprocessed (resize and normalization).
3. The trained CNN model analyzes the image.
4. The model predicts one of the four tumor classes.
5. The application displays the predicted class along with its confidence score.

---

## 📊 Model Performance

| Metric | Value |
|---------|-------|
| Training Accuracy | XX% |
| Validation Accuracy | XX% |
| Test Accuracy | XX% |

> Replace the values with your actual model performance.

---

## 🚀 Installation

Clone the repository

```bash
git clone https://github.com/your-username/Brain-Tumor-Detection.git
```

Navigate to the project folder

```bash
cd Brain-Tumor-Detection
```

Install dependencies

```bash
pip install -r requirements.txt
```

Run the application

```bash
python app.py
```

Open your browser and visit:

```
http://127.0.0.1:5000
```

---

## 📷 Application Preview

### Home Page

*(Add screenshot here)*

### Prediction Result

*(Add screenshot here)*

---

## 📚 Dataset

The model is trained on a Brain MRI dataset containing four classes:

- Glioma Tumor
- Meningioma Tumor
- Pituitary Tumor
- No Tumor

**Note:** The dataset used for training is not included in this repository.

---

## 🔮 Future Enhancements

- Grad-CAM visualization
- Docker support
- REST API
- Cloud deployment (AWS/Azure)
- User authentication
- Medical report generation

---

## ⚠️ Disclaimer

This project is developed for educational and research purposes only. It is **not intended to replace professional medical diagnosis.**

---

## 👩‍💻 Author

**Shreya Singh**
