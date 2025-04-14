# Emotion-Detection

**🤖 Emotion Detection Robot Assistant** This project is an AI-powered Emotion Detection Robot that analyzes a user's facial emotion in real-time and responds accordingly using natural conversation. It combines deep learning for emotion classification with conversational AI and voice synthesis to create a responsive, empathetic assistant.

-----
## 🧠 How It Works

- A Convolutional Neural Network (CNN) trained on facial emotion datasets detects the user's current emotional state.
- The detected emotion is used as a contextual input to tailor responses from OpenAI's GPT (ChatGPT) API.
- Responses are then voiced using Eleven Labs' voice synthesis API, creating a smooth and expressive audio interaction.
- The assistant reacts differently based on emotions like happy, sad, angry, surprised, etc., offering more human-like engagement.

-----

## 🛠️ Technologies and Data set Used

- TensorFlow / Keras – For CNN-based emotion classification
- MobileNetV2 - Lightweight and fast**, ideal for embedded/mobile scenarios
- EfficientNetB0 – Lightweight, high-accuracy backbone for real-time inference
- OpenAI GPT API – To generate emotionally aware responses
- Eleven Labs API – For high-quality speech synthesis
- Flask / Streamlit / PyQt (optional) – For interactive UI (customizable)
- OpenCV – For live webcam feed and face detection
- Ideal for therapy bots, customer service kiosks, or personal digital assistants where empathetic interaction enhances user experience
- FER-2013 dataset

----

## 💡 Use Case

Ideal for therapy bots, customer service kiosks, or personal digital assistants where empathetic interaction enhances user experience.

----

### 📊 Model Training Summary

1. Trial #0

| Epoch | Training Accuracy | Validation Accuracy | Validation Loss |
|-------|-------------------|---------------------|-----------------|
| 1     | 24.84%            | 30.45%              | 1.7278          |
| 2     | 33.59%            | 40.15%              | 1.5921          |
| 3     | 41.11%            | 37.57%              | 1.5819          |
| 4     | 45.72%            | 42.46%              | 1.4935          |
| 5     | 50.13%            | 43.02%              | 1.4738          |
| 6     | 54.05%            | 44.34%              | 1.4694          |
| 7     | 57.51%            | 43.02%              | 1.5424          |
| 8     | 61.34%            | 43.16%              | 1.5627          |
| 9     | 64.34%            | 44.13%              | 1.5963          |
| 10    | 69.85%            | 45.60%              | 1.6096          |
| 11    | 75.47%            | 43.92%              | 1.7635          |
| 12    | 78.93%            | 43.30%              | 1.9147          |
| 13    | 83.36%            | 44.76%              | 2.0202          |
| 14    | 87.78%            | 44.32%              | 2.2199          |
| 15    | 91.36%            | 45.04%              | 2.3622          |
| 16    | 93.60%            | 43.02%              | 2.7045          |
| 17    | 95.00%            | 45.81%              | 2.8669          |
| 18    | 97.77%            | 44.41%              | 3.1052          |
| 19    | 98.22%            | 45.25%              | 3.3375          |
| 20    | 99.10%            | 44.90%              | 3.6605          |

![Trial 0](https://github.com/Kinji301/yh/blob/main/trial_0.png?raw=true)




