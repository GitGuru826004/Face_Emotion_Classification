# Face Emotion Recognition 🎭

A full‑stack web application that detects human emotions in faces using a Convolutional Neural Network trained on the [FER‑2013](https://www.kaggle.com/datasets/msambare/fer2013) dataset.

---

## 🚀 Features

- **Real‑time Emotion Detection**  
  Capture from webcam or upload an image to classify one of seven emotions:  
  `Angry`, `Disgust`, `Fear`, `Happy`, `Sad`, `Surprise`, `Neutral`.

- **Pre‑trained CNN Model**  
  Keras/TensorFlow model (`model_weights.h5`) fine‑tuned on FER‑2013.

- **Interactive Frontend**  
  JavaScript & CSS client for live preview, emotion overlay, and responsive design.

- **RESTful API Backend**  
  Flask‑based `app.py` exposes `/predict` endpoint for image inference.

- **Exploratory Notebook**  
  Jupyter notebook for data exploration, model architecture, training history, and performance metrics.


## 📁 Repository Structure

```plaintext
face-emotion-recognition/
├── client/                     # Frontend (HTML/CSS/JS)
├── server/                     # Backend (Flask API & model inference)
├── images/                     # Static assets & UI screenshots
├── Face emotion Recognition.ipynb  # EDA, model training & evaluation
├── app.py                      # Flask application entrypoint
├── model_weights.h5            # Pre‑trained CNN weights
├── requirements.txt            # Python dependencies
└── README.md                   # This overview

```


## 🤝 Collaborators

- **Anupam Garg**: Data preprocessing, CNN model training, and saving model weights & results
