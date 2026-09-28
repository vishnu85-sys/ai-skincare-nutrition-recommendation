# AI-Powered Multilingual Skincare & Nutrition Recommendation System

An AI-powered web application that analyzes a skin image, predicts the skin type, and provides personalized skincare and nutrition recommendations.

## Features

- Skin-type classification from uploaded images
- AI-based image prediction using TensorFlow
- Skincare recommendations based on predicted skin type
- Nutrition recommendations with foods to eat and avoid
- Multilingual support
- Text-to-speech audio recommendations
- Flask-based web application
- Responsive web interface

## Technologies Used

- Python
- TensorFlow 2.15
- Keras
- Flask
- NumPy
- Pandas
- Scikit-learn
- HTML5
- CSS3
- JavaScript
- MySQL / data-processing components

## Machine Learning

The application uses a trained deep-learning image classification model to identify skin types from uploaded images.

Supported categories in the application include:

- Oily Skin
- Dry Skin
- Acne-Prone Skin

## Application Workflow

```text
Upload Skin Image
        ↓
Image Preprocessing
        ↓
Deep Learning Model
        ↓
Skin-Type Prediction
        ↓
Skincare Recommendations
        ↓
Nutrition Recommendations
        ↓
Multilingual / Audio Output

AI-Skincare-Nutrition-Recommendation
│
├── app.py
├── main.py
├── audio.py
├── foods_data.py
├── recommendations_data.py
├── model_training.ipynb
├── skin_classification_model.keras
├── requirements.txt
│
├── Skin-Type-Recognition/
│
├── assets/
├── static/
├── templates/
└── translations/
    ├── en.json
    ├── hi.json
    └── te.json
