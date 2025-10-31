AI Integrated Healthcare System
Deep Learning | Pill Identification | Symptom-Based Consultation | Pharmacy Navigation
📋 Overview
The AI Integrated Healthcare System is a Flask-based web application that integrates Deep Learning and Artificial Intelligence to provide healthcare assistance.
It enables users to:

Identify pills using image recognition,

Predict diseases based on entered symptoms, and

Locate nearby pharmacies using Google Maps.

This project aims to bridge the gap between users and primary healthcare by providing instant, AI-powered insights.

🚀 Key Features
💊 Pill Identification (Deep Learning)
Users upload an image of a tablet or capsule.

A Convolutional Neural Network (CNN) model trained on pill images predicts the medicine name.

Displays detailed information like composition, dosage, and side effects.

🩺 Symptom-Based Disease Prediction (AI)
Takes symptoms as input.

Predicts possible diseases using a hybrid AI model (Random Forest / Deep Neural Network).

Suggests basic remedies and precautions.

🏥 Pharmacy Navigation
Integrates Google Maps API to locate nearby pharmacies.

Displays directions, timings, and contact details

| Category               | Technology                         |
| ---------------------- | ---------------------------------- |
| **Frontend**           | HTML5, CSS3, JavaScript, Bootstrap |
| **Backend**            | Flask (Python)                     |
| **AI / Deep Learning** | TensorFlow, Keras, Scikit-learn    |
| **Computer Vision**    | OpenCV, NumPy, Pillow              |
| **Database**           | SQLite / MySQL                     |
| **APIs**               | Google Maps API                    |
| **Data Visualization** | Matplotlib, Seaborn                |


⚙️ System Workflow
User Input Layer:

Symptom text input or pill image upload.

AI Processing Layer:

Symptom-based AI Model → Predicts probable diseases.

CNN Model → Identifies pills from uploaded images.

Integration Layer:

Connects predictions with stored medicine/disease data.

Calls Google Maps API for nearby pharmacy suggestions.

Response Layer:

Displays predictions, medical details, and maps on the UI.

🧩 Deep Learning Models
💊 Pill Identification Model
Type: Convolutional Neural Network (CNN)

Input: Pill image (resized to 128×128)

Output: Predicted pill name and details

Libraries: TensorFlow, Keras, OpenCV

Performance: ~92% accuracy (based on test dataset)

🩺 Symptom Analysis Model
Type: Deep Neural Network / Random Forest Classifier

Dataset: Symptom-Disease dataset (from Kaggle & WHO open data)

Output: Top 3 probable diseases with confidence scores
