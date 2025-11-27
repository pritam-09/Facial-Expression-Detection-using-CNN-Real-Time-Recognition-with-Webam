
# Real-Time Facial Expression Detection System

**CNN Model | Live Webcam Integration | Emotion Classification**

This project implements a **real-time facial expression recognition system** using a **Convolutional Neural Network (CNN)** and **OpenCV**. The system captures live video from a webcam, detects faces, and classifies emotions such as **Happy, Sad, Angry, and Surprise** in real time.

---

## 🚀 Features

* Real-time face detection using OpenCV
* Emotion recognition with a trained CNN model
* Smooth live video stream processing
* Supports multiple emotion classes:

  * Happy
  * Sad
  * Angry
  * Surprise
* Works with any standard laptop/USB webcam

---

## 🧠 Model Details

* Built with a **custom CNN** trained on an emotion-labelled dataset
* Preprocessing includes grayscale conversion, resizing, and normalization
* Model outputs probability scores for each emotion
* Deployed using OpenCV for live predictions

---

## 📁 Project Structure

```
facial-expression-detection/
│
├── model/
│   └── emotion_model.h5
│
├── src/
│   ├── detector.py
│   ├── model_loader.py
│   └── real_time.py
│
├── haarcascade_frontalface_default.xml
├── requirements.txt
└── README.md
```

---

## ⚙️ Installation & Setup

### 1. Clone the repository

```
git clone https://github.com/yourusername/your-repo-name.git
cd your-repo-name
```

### 2. Install dependencies

```
pip install -r requirements.txt
```

### 3. Run the real-time emotion detector

```
python real_time.py
```

---

## 🔍 How It Works

### 1. Capture webcam frames

OpenCV captures each frame and converts it to grayscale.

### 2. Detect faces

Using Haar Cascade classifier:

```
cv2.CascadeClassifier('haarcascade_frontalface_default.xml')
```

### 3. Preprocess the face

* Resize to model input size
* Normalize pixel values

### 4. Predict emotion using the CNN

Model outputs emotion class probabilities.

### 5. Display results

Emotion labels are drawn above the detected face in the live feed.

---

## 🧪 Example Output

**Live Webcam Feed:**

* Face detected
* Label displayed: *Happy*
* Bounding box drawn around face

---

## 📌 Future Enhancements

* Add more emotion categories
* Use MobileNet or EfficientNet for faster inference
* Add GUI using Tkinter / PyQt
* Deploy as a web app using Streamlit or Flask

---

## 🤝 Contributing

Pull requests are welcome!
For major changes, please open an issue first.

---

## 📄 License

MIT License

---

## 🔗 GitHub Link

(https://github.com/pritam-09/Facial-Expression-Detection-using-CNN-Real-Time-Recognition-with-Webam/tree/main)


---
