# Skin Disease Prediction Using Deep Learning 🩺

[cite_start]This project is an AI-powered assistant designed to catch skin diseases early when they are most treatable[cite: 31, 175]. [cite_start]By combining smart technology with medical imaging, it provides quick, reliable insights for conditions like Melanoma[cite: 3, 519]. [cite_start]It’s built to support doctors, reduce manual work, and give patients peace of mind through accessible, high-tech care[cite: 5, 263].

---

### 🌟 Key Features
* [cite_start]**Multi-Disease Classification**: Identifies seven distinct conditions: Actinic keratoses, Basal cell carcinoma, Benign keratosis, Dermatofibroma, Melanocytic nevi, Melanoma, and Vascular lesions[cite: 8, 15, 687].
* [cite_start]**High-Tech Brain**: Uses the **DenseNet** architecture and **CNN** algorithms to pick up on subtle visual patterns that might be missed by the human eye[cite: 164, 264].
* [cite_start]**Transfer Learning**: The model leverages pre-trained weights from millions of images, which are then "fine-tuned" specifically for dermatology to reach higher accuracy[cite: 167, 168].
* [cite_start]**Smart Image Cleanup**: Automatically handles common photo issues like bad lighting, noise, or distracting artifacts (like hair) to ensure the AI gets a clear view[cite: 581, 714].
* [cite_start]**User-Friendly Web App**: A simple **Flask** website where users can upload a photo and get an instant prediction with a confidence score[cite: 887, 1202].

---

### 🛠️ Technology Stack
* [cite_start]**Language**: Python[cite: 682].
* [cite_start]**Deep Learning**: Keras and TensorFlow[cite: 983, 1117].
* [cite_start]**Web Framework**: Flask[cite: 978].
* [cite_start]**Image Processing**: PIL (Pillow), NumPy, and OpenCV[cite: 979, 982].
* [cite_start]**Environment**: Visual Studio Code[cite: 682, 1053].

---

### 📋 System Requirements
* [cite_start]**Processor**: Intel Core Duo 2.0 GHz or higher[cite: 678].
* [cite_start]**RAM**: At least 1 GB[cite: 679].
* [cite_start]**Storage**: 20 GB of free space[cite: 680].
* [cite_start]**OS**: Windows 7 or newer[cite: 683].

---

### 📊 How It Works
1. [cite_start]**Data Collection**: Sourced from diverse medical databases like ISIC and HAM10000 to ensure the model sees many skin types[cite: 339, 441].
2. [cite_start]**Preprocessing**: The system resizes photos and uses median filtering to remove "noise" like skin hair or camera glare[cite: 581, 582].
3. [cite_start]**Feature Extraction**: The CNN learns to identify specific textures, color variations, and asymmetry in skin lesions[cite: 100].
4. [cite_start]**Prediction**: When a new image is uploaded, the AI compares it to its training and provides a diagnosis (e.g., "Melanoma") with a confidence percentage[cite: 972, 1210].

---

### 📂 Project Structure
* [cite_start]`app.py`: The heart of the web app that manages user requests and the AI model[cite: 977, 1053].
* [cite_start]`modelnew.json` & `modelnew.h5`: The pre-trained "brain" containing the rules and weights for detection[cite: 999, 1002].
* [cite_start]`templates/`: The visual part of the website, including Home, About, and Result pages[cite: 763, 790, 883].
* [cite_start]`static/`: Stores styles, fonts, and background images for the interface[cite: 809, 813].

---

### ⚖️ Ethical Note
[cite_start]This tool is built to assist doctors, not replace them[cite: 17, 454]. [cite_start]We prioritize data security and patient privacy, and we always recommend a professional biopsy for a final medical confirmation[cite: 300, 426].
