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

