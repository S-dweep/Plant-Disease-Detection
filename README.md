
# 🌿 Plant Disease Detection Web App

A deep learning-powered web application that detects diseases in plant leaves (currently supports **Corn**, **Potato**, and **Tomato**) using a trained CNN model. Built with **TensorFlow/Keras**, **OpenCV**, and **Streamlit** for an interactive frontend.

---

## 🔍 Demo

https://user-streamlit-app-link (Replace with your deployed app link)

---

## 📸 Sample Predictions

| Image | Prediction |
|-------|------------|
| ![Tomato](assets/tomato_leaf.jpg) | Tomato leaf with Bacterial Spot |
| ![Potato](assets/potato_leaf.jpg) | Potato leaf with Early Blight |
| ![Corn](assets/corn_leaf.jpg)     | Corn leaf with Common Rust     |

---

## 🧠 Model

- **Input**: 256x256 colored image of a leaf
- **Architecture**: Custom CNN (or mention if you used a pretrained model like MobileNet/VGG16)
- **Output Classes**:
  - 🌽 `Corn - Common Rust`
  - 🥔 `Potato - Early Blight`
  - 🍅 `Tomato - Bacterial Spot`

---

## 🚀 How It Works

1. Upload an image of a **leaf** (in `.jpg` format)
2. The app resizes and processes the image
3. The CNN model predicts the disease class
4. The result is shown with the predicted **plant** and **disease**

---

## 🛠️ Tech Stack

| Technology | Description |
|------------|-------------|
| 🐍 Python | Programming Language |
| 🧠 TensorFlow/Keras | Deep Learning Framework |
| 📷 OpenCV | Image Processing |
| 🌐 Streamlit | Web App Framework |

---

## 📂 Directory Structure

```
plant_disease_detection/
│
├── plant_disease.keras          # Trained model
├── app.py                       # Streamlit App
├── assets/                      # Sample leaf images
└── README.md
```

---

## 🔧 Setup Instructions

1. **Clone the repository**
```bash
git clone https://github.com/your-username/plant-disease-detection.git
cd plant_disease_detection
```

2. **Install dependencies**
```bash
pip install -r requirements.txt
```

3. **Run the app**
```bash
streamlit run app.py
```

---

## 📦 Requirements

Create a `requirements.txt` file:

```txt
streamlit
opencv-python
numpy
tensorflow
keras
```

---

## ✨ Features

- User-friendly interface
- Real-time predictions
- Lightweight, fast & responsive
- Expandable to more crops and diseases

---

## 🧪 Future Improvements

- Add more classes and datasets
- Support for mobile image capture
- Confidence scores and model explainability (e.g., Grad-CAM)

---

## 🤝 Contributing

Feel free to open issues or submit PRs! Contributions are welcome.

---
