Skin Disease Prediction Using Deep Learning
This project is an automated system designed to help identify skin diseases and cancers at an early stage. By using Deep Learning and the DenseNet architecture, the tool analyzes medical images to provide quick, reliable diagnostic support for both patients and healthcare professionals.


🌟 Key Features

Broad Detection Range: Classifies various conditions including Melanoma, Basal Cell Carcinoma, Actinic Keratosis, Benign Keratosis, Dermatofibroma, Melanocytic Nevi, and Vascular lesions .



Smart Architecture: Uses DenseNet to pick up on subtle visual patterns that might be missed by the human eye.



Transfer Learning: The model starts with knowledge from millions of general images and is then "fine-tuned" specifically for skin diseases to reach higher accuracy.



Image Cleanup: Automatically handles common photo issues like bad lighting, noise, or distracting artifacts (like hair) to ensure the AI gets a clear view.



Web Interface: A simple, user-friendly Flask website where anyone can upload a photo and get an instant prediction.


🛠️ Technology Behind the Project

Language: Python.



Brain Power: Keras and TensorFlow (Deep Learning frameworks).



Web Backend: Flask.



Image Processing: PIL (Pillow), NumPy, and OpenCV.



Developer Tools: Visual Studio Code.


📋 What You Need to Run It

Processor: Intel Core Duo 2.0 GHz or higher.


RAM: At least 1 GB.


Storage: 20 GB of free space.


System: Windows 7 or newer.

📊 How It Works

Gathering Data: We use thousands of high-quality, labeled skin images from medical databases like ISIC and HAM10000.


Preprocessing: The system resizes photos and filters out "noise" like skin hair or camera glare.


Training: The CNN (Convolutional Neural Network) learns to identify the specific texture, color, and symmetry of different lesions.


Prediction: When a new image is uploaded, the AI compares it to everything it has learned and provides a diagnosis with a confidence score.

📂 Project Folder Structure

app.py: The heart of the web app that manages user requests and the AI model.


modelnew.json / modelnew.h5: The pre-trained "brain" containing the rules and weights for detection .


templates/: The visual part of the website (Home, About, and Result pages).


static/: Where we store CSS styles and images for the website design.

⚖️ A Note on Ethics
This tool is built to assist doctors, not replace them. We prioritize data security and patient privacy, and we always recommend a professional biopsy for a final medical confirmation.
