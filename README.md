# 🎙️ Speech Emotion & DeepFake Image Recognition

This project integrates **Speech Emotion Recognition (SER)** and **DeepFake Image Detection** using **Python and Deep Learning**.  
It aims to identify the **emotional state of a speaker** from their voice and detect whether a **given image/video frame is real or deepfake**, helping improve content authenticity and human-computer interaction systems.

---

## 📘 Overview

The system is divided into two main components:

1. **Speech Emotion Recognition (SER)**
   - Detects emotions such as **Happy, Sad, Angry, Fearful, Disgust, Pleasant Surprise, and Neutral**.
   - Trained using the **Toronto Emotional Speech Set (TESS)** dataset.
   - Uses **MFCC (Mel-Frequency Cepstral Coefficients)** for audio feature extraction.

2. **DeepFake Image Recognition**
   - Classifies images as **Real** or **Fake** using deep neural networks.
   - Uses **VGG16/VGG19** architectures with transfer learning for high accuracy.
