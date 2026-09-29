# Emotion Detector - Learning Project

A Flask-based learning project for emotion detection using IBM Watson NLP.

## Structure

- `EmotionDetection/emotion_detection.py` - Watson NLP integration
- `EmotionDetection/__init__.py` - package initializer
- `test_emotion_detection.py` - unit tests
- `server.py` - Flask web application
- `requirements.txt` - dependencies

## Project Description

This project detects emotions from user-provided text using the IBM Watson NLP emotion detection service. It returns emotion scores for anger, disgust, fear, joy, and sadness, along with the dominant emotion.

## Features

- IBM Watson NLP emotion detection
- Emotion score extraction
- Dominant emotion identification
- Flask web interface
- Unit testing
- Error handling
- Static code analysis using Pylint

## Running the Application

Install the required dependencies:

```bash
pip install -r requirements.txt
