🌿 Plant Disease Detection Web App
A deep learning-powered web application that detects diseases in plant leaves (currently supports Corn, Potato, and Tomato) using a trained CNN model. Built with TensorFlow/Keras, OpenCV, and Streamlit for an interactive frontend.

🔍 Demo
https://user-streamlit-app-link (Replace with your deployed app link)

📸 Sample Predictions
Image	Prediction
Tomato leaf with Bacterial Spot
Potato leaf with Early Blight
Corn leaf with Common Rust

🧠 Model
Input: 256x256 colored image of a leaf

Architecture: Custom CNN (or mention if you used a pretrained model like MobileNet/VGG16)

Output Classes:

🌽 Corn - Common Rust

🥔 Potato - Early Blight

🍅 Tomato - Bacterial Spot

🚀 How It Works
Upload an image of a leaf (in .jpg format)

The app resizes and processes the image

The CNN model predicts the disease class

The result is shown with the predicted plant and disease

🛠️ Tech Stack
Technology	Description
🐍 Python	Programming Language
🧠 TensorFlow/Keras	Deep Learning Framework
📷 OpenCV	Image Processing
🌐 Streamlit	Web App Framework

📂 Directory Structure
bash
Copy
Edit
plant_disease_detection/
│
├── plant_disease.keras          # Trained model
├── app.py                       # Streamlit App
├── assets/                      # Sample leaf images
└── README.md
🔧 Setup Instructions
Clone the repository

bash
Copy
Edit
git clone https://github.com/your-username/plant-disease-detection.git
cd plant-disease-detection
Install dependencies

bash
Copy
Edit
pip install -r requirements.txt
Run the app

bash
Copy
Edit
streamlit run app.py
📦 Requirements
Create a requirements.txt file:

txt
Copy
Edit
streamlit
opencv-python
numpy
tensorflow
keras
✨ Features
User-friendly interface

Real-time predictions

Lightweight, fast & responsive

Expandable to more crops and diseases

🧪 Future Improvements
Add more classes and datasets

Support for mobile image capture

Confidence scores and model explainability (e.g., Grad-CAM)

🤝 Contributing
Feel free to open issues or submit PRs! Contributions are welcome.
