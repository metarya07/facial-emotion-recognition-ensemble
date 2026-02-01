# Facial Emotion Recognition using Ensemble Vision Transformers

This project implements a real-time facial emotion recognition system using
an ensemble of Vision Transformer (ViT) models. It supports live webcam capture
in Google Colab, face alignment using MediaPipe, and human-in-the-loop feedback
for incremental retraining.

## Features
- Ensemble of 3 ViT-based FER models
- Face detection and alignment using MediaPipe
- Real-time webcam capture in Google Colab
- Confidence-based emotion prediction
- User feedback for correcting labels
- Incremental retraining using a linear classification head
- Performance analysis (accuracy, confusion matrix, emotion distribution)

## Emotion Classes
Angry, Disgust, Fear, Happy, Sad, Surprise, Neutral

## Tech Stack
- Python
- PyTorch
- Hugging Face Transformers
- MediaPipe
- OpenCV
- NumPy, Pandas, Matplotlib

## How to Run (Google Colab)
1. Open the notebook in Google Colab
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
****
