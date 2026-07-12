# 🧠 Brain Tumor Detection using Deep Learning

A deep learning-based web application for automatic brain tumor classification from MRI scans. The system utilizes a Convolutional Neural Network (CNN) to classify brain MRI images into four categories with over **90% accuracy**, providing fast and reliable predictions through an intuitive Flask-based web interface.

---

## 🚀 Features

- 🧠 Multi-class Brain Tumor Classification
- 📤 Upload MRI images for prediction
- ⚡ Real-time inference using a trained CNN model
- 📊 Displays prediction confidence score
- 🌐 User-friendly Flask web application
- 📱 Responsive interface
- 🎯 High prediction accuracy (>90%)

---

## 🩺 Tumor Categories

| Class | Description |
|-------|-------------|
| ✅ No Tumor | Healthy Brain MRI |
| 🔴 Glioma | Glioma Brain Tumor |
| 🟡 Meningioma | Meningioma Brain Tumor |
| 🔵 Pituitary | Pituitary Brain Tumor |

---

# 🛠️ Tech Stack

### Machine Learning
- Python
- TensorFlow
- Keras
- OpenCV
- NumPy
- Scikit-learn

### Backend
- Flask

### Frontend
- HTML5
- CSS3
- JavaScript

### Tools
- Git
- GitHub
- Kaggle

---

# 📂 Project Structure

```text
Brain-Tumor-Detection/
│
├── app.py
├── requirements.txt
├── README.md
├── .gitignore
│
├── model/
│   └── brain_tumor.keras
│
├── static/
│   ├── css/
│   ├── js/
│   └── images/
│
├── templates/
│   ├── index.html
│   └── result.html
│
└── uploads/
```

---

# ⚙️ Working

1. Upload an MRI brain scan.
2. The image is preprocessed and resized.
3. The CNN model extracts important features.
4. The trained model predicts the tumor category.
5. The application displays the predicted class along with its confidence score.

---

# 📈 Model Performance

| Metric | Score |
|---------|-------|
| Training Accuracy | **95%+** |
| Validation Accuracy | **92%+** |
| Test Accuracy | **90%+** |

> The model achieved consistently high performance across training, validation, and testing datasets, making it suitable for reliable brain MRI classification.

---

# 🚀 Installation

Clone the repository

```bash
git clone https://github.com/your-username/Brain-Tumor-Detection.git
```

Navigate to the project directory

```bash
cd Brain-Tumor-Detection
```

Install the required dependencies

```bash
pip install -r requirements.txt
```

Run the Flask application

```bash
python app.py
```

Open your browser and visit

```
http://127.0.0.1:5000
```


# 📚 Dataset

The model is trained on a Brain MRI dataset consisting of four classes:

- No Tumor
- Glioma Tumor
- Meningioma Tumor
- Pituitary Tumor

> **Note:** The dataset used for training is not included in this repository.

---

# 🔮 Future Enhancements

- Vision Transformer (ViT) implementation
- Transfer Learning using EfficientNet and ResNet
- Grad-CAM visualization for model explainability
- Docker containerization
- Cloud deployment (AWS, Azure, or GCP)
- REST API integration
- User authentication and history management

---

# ⚠️ Disclaimer

This project is developed for educational and research purposes only. It is not intended to replace professional medical diagnosis or clinical decision-making.

---

# 👩‍💻 Author

**Shreya Singh**


---

## ⭐ If you found this project useful, consider giving it a Star!
