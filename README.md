Room Brightness Classifier with Keras + Teachable Machine
This project uses Google Teachable Machine to train a binary image classifier that detects whether a room is bright or dark, and then deploys the model using Python and Keras.

📷 Project Overview
Classes:
bright room ☀️ — well-lit spaces

dark room 🌑 — low-light or dimly lit spaces

Training Source:
Built using Teachable Machine

7 total training images:

4 for bright room

3 for dark room


🧪 Model Architecture
Framework: TensorFlow/Keras

Model format: .h5 exported from Teachable Machine

Input shape: (1, 224, 224, 3) for 224×224 RGB images

🚀 How to Use
🔧 Prerequisites

bash

pip install tensorflow pillow numpy
📁 Files Required
keras_Model.h5 — trained model

labels.txt — text file with class labels (one per line)

Your test image (e.g., room.jpg)

نسخ
Class: bright room
Confidence Score: 0.98
The model successfully predicts whether the image depicts a bright or dark room with high accuracy.

🧠 Use Cases
Smart lighting automation

Contextual user interfaces (day/night modes)

Surveillance camera environment awareness

📌 Notes
More training images = better accuracy!

You can improve classification by balancing classes and using different lighting types (natural vs artificial).

