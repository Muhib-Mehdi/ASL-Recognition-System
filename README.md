# 🧠 ASL Recognition System

A deep learning–based system that detects **American Sign Language (ASL) gestures in real time** using a webcam.  
This project aims to improve communication accessibility for people with speech or hearing impairments.

---

## 🚀 Features
- Real-time hand gesture detection
- High prediction accuracy (97%)
- Webcam live feed classification
- Trained using a Convolutional Neural Network (CNN)
- Uses MediaPipe for efficient hand-tracking

---

## 🛠️ Technologies Used
| Technology | Purpose |
|-----------|---------|
| Python | Primary Language |
| TensorFlow / Keras | Model Training & Prediction |
| OpenCV | Webcam & Image Processing |
| MediaPipe | Hand Tracking & Keypoint Extraction |
| NumPy / Pandas | Data Processing |

---

## 📂 Project Structure (example)
ASL-Recognition-System/
│── model/ # Trained model files
│── dataset/ # Dataset used for training
│── src/ # Main application code
│ ├── train.py
│ ├── predict.py
│ ├── utils.py
│── requirements.txt
│── README.md
│── app.py # Main real-time detection script

---

## 🔧 Installation & Setup
#1️⃣ Clone the repository  
```bash
git clone https://github.com/Muhib-Mehdi/ASL-Recognition-System.git
cd ASL-Recognition-System
```

#2️⃣ Install dependencies
```bash
pip install -r requirements.txt
```
#3️⃣ Run the application
```bash
python app.py
```

## 🧠 Model Details

Architecture: Convolutional Neural Network (CNN)
Dataset: ASL hand gesture dataset
Accuracy: 97%
Training framework: TensorFlow + Keras

## 📌 Future Improvements

Add support for more ASL alphabets & words
Export model to mobile app
Add UI for better interaction
Convert model to ONNX / TFLite

## 👨‍💻 Developer

Muhib Mehdi
If you like this project, feel free to ⭐ the repository!

## 📜 License

This project is open-source under the MIT License.
