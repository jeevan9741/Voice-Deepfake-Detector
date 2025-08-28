🎙️ Voice Deepfake Detection

This project detects whether a given speech audio is Real (Human) or Fake (TTS/Deepfake).
It uses MFCC feature extraction + Machine Learning models (Logistic Regression / Random Forest / CNN).
A simple and attractive Streamlit app is included for uploading .wav files and visualizing results.

✨ Features

🎤 Upload audio files (.wav)

📊 Detect whether the voice is Real or Fake

🔢 Shows probability score (Real vs Fake)

🎶 Visualizes Spectrograms and MFCC features

📈 Plots accuracy metrics and confusion matrix

🖥️ Attractive UI with Streamlit for exam demos & presentations

📂 Project Structure
TTS-Detector/
│── data/
│   ├── real/   # Put real human audio (.wav)
│   ├── fake/   # Put fake/TTS audio (.wav)
│
│── app.py      # Streamlit UI
│── train.py    # Script to train the model
│── model.pkl   # Saved trained model
│── requirements.txt
│── README.md

⚙️ Installation

Clone the repo and install dependencies:

[git clone https://github.com/yourusername/TTS-Detector.git](https://github.com/jeevan9741/Voice-Deepfake-Detector/tree/main)
cd TTS-Detector
pip install -r requirements.txt

🚀 Usage
1️⃣ Train the model
python train.py


This will train the classifier and save model.pkl.

2️⃣ Run the Streamlit app
streamlit run app.py


Open the link in your browser to interact with the app.

📊 Example Outputs

Prediction Result: ✅ Real / ❌ Fake

Accuracy Score: e.g., 92.5%

Plots:

Spectrogram of audio

MFCC feature plot

Probability distribution (Real vs Fake)

Confusion matrix

🛠️ Tech Stack

Python 🐍

Librosa 🎶 (Audio Processing)

Scikit-learn 🤖 (ML Models)

Streamlit ⚡ (Web UI)

Matplotlib & Seaborn 📊 (Plots)

📌 Future Improvements

Add deep learning (CNN/LSTM) for higher accuracy

Support more audio formats (.mp3, .flac)

Deploy on HuggingFace / Heroku for live demo

👨‍💻 Author

Made by JEEVAN ✨
For academic/research/demo purposes.
