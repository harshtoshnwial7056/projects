# 🎙️ VoiceShield – AI vs Human Voice Detector

VoiceShield is a Python-based tool that helps **detect whether a voice recording is AI-generated or from a real human**. It uses audio feature extraction and a neural network classifier trained on sample data to identify potential voice frauds and impersonations.

---

## 🚀 How It Works

1. The model extracts features like **MFCCs (Mel-Frequency Cepstral Coefficients)** from audio files.
2. A small neural network (built with PyTorch) is trained to distinguish between **AI-generated voices** and **human voices**.
3. It gives a **probability score (0 to 1)** — closer to 1 means more likely to be AI.

---

## 🧠 Technologies Used

| Tool/Library     | Purpose                                 |
|------------------|------------------------------------------|
| Python 3.x       | Main language                           |
| PyTorch          | Neural network model training           |
| NumPy, Pandas    | Data manipulation                       |
| Librosa          | Audio processing (MFCCs, sampling, etc.)|
| SoundDevice      | For real-time recording (optional)      |
| Matplotlib       | For visualizing training performance    |
| Scikit-learn     | Accuracy scoring                        |

---

## 📁 Folder Structure
voice_shild/
├── ai_detector.pth # Trained model (not included in repo)
├── detect_ai_voice.py # Function to predict AI/Human from audio
├── record_and_detect.py # (Optional) Record and detect in one go
├── train_model.py # Model training script
├── human_voices/ # Folder with human audio files (.wav)
├── ai_voices/ # Folder with AI audio files (.wav)
├── test.wav # Sample input file to te
2. Install Dependencies
Edit
pip install -r requirements.txt
If requirements.txt is not available, install manually:

