# Emotion Detector using IBM Watson NLP

This project is an AI-based web application for emotion detection in customer feedback using the embedded IBM Watson NLP service.

## Features

- Detects emotions: anger, disgust, fear, joy, and sadness
- Identifies the dominant emotion
- Web-based UI using Flask
- Error handling for blank input
- Unit tested and PEP8-compliant

## Structure

```
emotion-detector-watson/
├── EmotionDetection/
│   ├── __init__.py
│   └── emotion_detection.py
├── test_emotion_detection.py
├── server.py
├── static/
│   └── mywebscript.js
├── templates/
│   └── index.html
├── requirements.txt
└── README.md
```

## Run the App

```bash
pip install -r requirements.txt
python3 server.py
```

Visit `http://localhost:5000` in your browser.

## Run Unit Tests

```bash
python3 test_emotion_detection.py
```

## Author

IBM Skills Network Final Project - Emotion Detection
