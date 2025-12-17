🎯 Final Flutter Project: App Logo Classifier
LogoVision is a specialized mobile application built with Flutter that utilizes Machine Learning to identify popular social media and e-commerce logos in real-time. By leveraging a custom-trained TensorFlow Lite model, the app provides instant brand recognition directly on your smartphone.

📖 Table of Contents
✨ About the Project

📦 Supported Brands
The model is currently trained to recognize the following 10 classes:

📱 Social Media: Facebook, Instagram, Tik-Tok, Snapchat, X (formerly Twitter), YouTube.

🛍️ E-Commerce: Shopee, Lazada.

💳 FinTech/Music: G-Cash, Spotify.

🚀 Key Features
📸 Live Camera Feed: Point your camera at a screen or printout to identify the logo.

🖼️ Gallery Picker: Import saved images to run the classifier.

📊 Confidence Scoring: Displays the percentage of certainty for each prediction.

🎨 Clean UI: A minimalist interface focused on user experience.

## 📺 Video Demo
Check out **LogoVision** in action! See how it classifies the 10 different app categories with high accuracy.
[![Watch the video](https://markdown-videos-api.jorgenkh.no/youtube/NRShV7QvLiA)](https://www.youtube.com/watch?v=NRShV7QvLiA)

🧠 How it Works
The application uses a Convolutional Neural Network (CNN) optimized for mobile.

Pre-processing: The Flutter app captures an image and crops/resizes it to the dimensions required by the model.

Inference: The tflite interpreter runs the image data through the model weights.

Post-processing: The app maps the resulting index to the corresponding brand name (e.g., Index 2 -> Instagram) and updates the UI.

✨ About the Project
In a world saturated with digital platforms, this project demonstrates the power of On-Device AI. Unlike cloud-based vision APIs, this Flutter app processes images locally. This ensures:

Privacy: Images never leave the device.

Speed: Near-instant classification without network latency.

Accessibility: Works offline in remote areas.

📦 Supported Brands
The model is currently trained to recognize the following 10 classes:

📱 Social Media: Facebook, Instagram, Tik-Tok, Snapchat, X (formerly Twitter), YouTube.

🛍️ E-Commerce: Shopee, Lazada.

💳 FinTech/Music: G-Cash, Spotify.

🚀 Key Features
📸 Live Camera Feed: Point your camera at a screen or printout to identify the logo.

🖼️ Gallery Picker: Import saved images to run the classifier.

📊 Confidence Scoring: Displays the percentage of certainty for each prediction.

🎨 Clean UI: A minimalist interface focused on user experience.

🧠 How it Works
The application uses a Convolutional Neural Network (CNN) optimized for mobile.

Pre-processing: The Flutter app captures an image and crops/resizes it to the dimensions required by the model.

Inference: The tflite interpreter runs the image data through the model weights.

Post-processing: The app maps the resulting index to the corresponding brand name (e.g., Index 2 -> Instagram) and updates the UI.
