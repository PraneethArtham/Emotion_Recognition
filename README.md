🎤 Speech Emotion Recognition Web App
A machine learning–powered web application that detects human emotions from speech audio using MFCC features and an SVM classifier, deployed with Streamlit.

🌐 Live Application Overview
This web app allows users to:

Upload a .wav audio file

Analyze the speech signal

Predict the emotion expressed in the audio

🎯 Supported Emotions

Neutral

Calm

Happy

Sad

Angry

Fear

Disgust

Surprise

🧠 How It Works (High‑Level)
Audio Input

User uploads a WAV file through the web interface

Feature Extraction

Mel Frequency Cepstral Coefficients (MFCCs) are extracted from audio

MFCCs capture speech characteristics similar to human hearing

Model Prediction

A Support Vector Machine (SVM) model classifies the emotion

Output is displayed instantly on the UI

🛠️ Tech Stack
Category	Technology
Language	Python
ML Model	Support Vector Machine (SVM)
Feature Extraction	Librosa (MFCC)
Web Framework	Streamlit
Dataset	RAVDESS (Ryerson Audio‑Visual Dataset)
Libraries	NumPy, Pandas, Scikit‑Learn
📁 Project Structure
emotion-recognition/
│
├── app.py                 # Streamlit frontend
├── backend.py             # ML logic (training + inference)
├── audio/                 # Training dataset (RAVDESS)
├── uploads/               # Uploaded audio files
├── requirements.txt
└── README.md
🚀 How to Run the Project Locally
1️⃣ Clone the Repository
git clone https://github.com/your-username/emotion-recognition.git
cd emotion-recognition
2️⃣ Install Dependencies
pip install -r requirements.txt
3️⃣ Run the Web App
streamlit run app.py
The app will open automatically in your browser.

📊 Machine Learning Details
Algorithm: Support Vector Machine (RBF Kernel)

Features: 40 MFCC coefficients

Scaling: StandardScaler

Train-Test Split: 80% / 20%

Dataset: RAVDESS (Emotion‑labeled speech dataset)

📈 Results
Achieved high classification accuracy on validation data

SVM performed better than Random Forest for MFCC‑based features

Real‑time predictions through web UI

🎯 Use Cases
Emotion analysis in voice assistants

Mental health monitoring systems

Call‑center sentiment analysis

Human‑computer interaction (HCI)

AI‑based speech analytics

🔮 Future Enhancements
🎙️ Live microphone recording

🧠 Gender detection from voice

📊 Confusion matrix & model insights

☁️ Cloud deployment (Streamlit Cloud / AWS)

📱 Mobile‑friendly UI

👨‍💻 Contributors
Mohammed Ghias Pasha

Artham Praneeth


### Dataset:https://www.kaggle.com/datasets/uwrfkaggler/ravdess-emotional-speech-audio


### testing Audio:https://www.kaggle.com/datasets/pavanelisetty/sample-audio-files-for-speech-recognition
