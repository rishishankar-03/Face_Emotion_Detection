# 😄 Face Emotion Detection

This project is a deep learning-based **Facial Emotion Detection System** that classifies human emotions based on facial expressions. It uses a Convolutional Neural Network (CNN) model trained on facial image datasets and provides a simple Python-based interface to test the model in real-time.

---

## 📌 Features

- Real-time facial emotion recognition using a webcam  
- Detects emotions like: **Happy, Sad, Angry, Fearful, Surprised, Neutral, Disgusted**  
- Pre-trained model included (`emotiondetector.h5`)  
- Simple and clean UI using OpenCV  
- Built with TensorFlow/Keras  

---

## 🚀 How to Run

### 1. Clone the Repository

git clone https://github.com/rishishankar-03/Face_Emotion_Detection.git  
cd Face_Emotion_Detection

### 2. Install Dependencies

pip install -r requirements.txt

### 3. Run the Application

python app.py

This will open your webcam and start detecting emotions in real-time.

---

## 🧠 Model Training

The training is done using a CNN defined in `TrainModel.ipynb`. You can open and run this notebook in Jupyter if you want to retrain the model.

---

## 📁 Project Structure

Face_Emotion_Detection/  
├── app.py                 → Main application script  
├── TrainModel.ipynb       → Jupyter notebook for training the model  
├── emotiondetector.h5     → Trained CNN model  
├── emotiondetector.json   → Model architecture (optional)  
├── requirements.txt       → Python dependencies  
└── README.md              → Project documentation

---

## ✅ Requirements

- Python 3.x  
- OpenCV  
- TensorFlow / Keras  
- NumPy  

---

## ✨ Future Improvements

- Web-based interface with Flask or Streamlit  
- Support for video files  
- Improved accuracy with larger datasets  
- Integration with mobile camera or apps  

---

## 🙋‍♂️ Author

**Rishi Shankar**  
GitHub: https://github.com/rishishankar-03

---

## 📄 License

This project is open-source and free to use under the MIT License.
