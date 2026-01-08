# Skin Disease Prediction Using Deep Learning 🩺

This project is an AI-powered assistant designed to catch skin diseases early when they are most treatable. By combining smart technology with medical imaging, it provides quick, reliable insights for conditions like Melanoma. It’s built to support doctors, reduce manual work, and give patients peace of mind through accessible, high-tech care.

---

### 🌟 Key Features
* **Multi-Disease Classification**: Identifies seven distinct conditions: Actinic keratoses, Basal cell carcinoma, Benign keratosis, Dermatofibroma, Melanocytic nevi, Melanoma, and Vascular lesions.
* **High-Tech Brain**: Uses the **DenseNet** architecture and **CNN** algorithms to pick up on subtle visual patterns that might be missed by the human eye.
* **Transfer Learning**: The model leverages pre-trained weights from millions of images, which are then "fine-tuned" specifically for dermatology to reach higher accuracy.
* **Smart Image Cleanup**: Automatically handles common photo issues like bad lighting, noise, or distracting artifacts (like hair) to ensure the AI gets a clear view.
* **User-Friendly Web App**: A simple **Flask** website where users can upload a photo and get an instant prediction with a confidence score.

---

### 🛠️ Technology Stack
* **Language**: Python.
* **Deep Learning**: Keras and TensorFlow.
* **Web Framework**: Flask.
* **Image Processing**: PIL (Pillow), NumPy, and OpenCV.
* **Environment**: Visual Studio Code.

---

### 📋 System Requirements
* **Processor**: Intel Core Duo 2.0 GHz or higher.
* **RAM**: At least 1 GB.
* **Storage**: 20 GB of free space.
* **OS**: Windows 7 or newer.

---

### 📊 How It Works
1. **Data Collection**: Sourced from diverse medical databases like ISIC and HAM10000 to ensure the model sees many skin types.
2. **Preprocessing**: The system resizes photos and uses median filtering to remove "noise" like skin hair or camera glare.
3. **Feature Extraction**: The CNN learns to identify specific textures, color variations, and asymmetry in skin lesions.
4. **Prediction**: When a new image is uploaded, the AI compares it to its training and provides a diagnosis (e.g., "Melanoma") with a confidence percentage.

---

### 📂 Project Structure
* `app.py`: The heart of the web app that manages user requests and the AI model.
* `modelnew.json` & `modelnew.h5`: The pre-trained "brain" containing the rules and weights for detection.
* `templates/`: The visual part of the website, including Home, About, and Result pages.
* `static/`: Stores styles, fonts, and background images for the interface.

---

### 🖼️ Output Screenshots

#### 1. Home Interface
The main dashboard where users interact with the application and upload skin lesion images for analysis.
<br>
<img width="775" alt="Home Interface" src="https://github.com/user-attachments/assets/34acfefe-2e59-49d0-a535-4d88023daee3" />

#### 2. Image Preprocessing
Visual representation of the data cleaning phase, showing how the system removes noise and artifacts to improve prediction accuracy.
<br>
<img width="778" alt="Image Preprocessing" src="https://github.com/user-attachments/assets/ae28d948-134e-4ef7-ad62-bec23e35efdf" />

---

### ⚖️ Ethical Note
This tool is built to assist doctors, not replace them. We prioritize data security and patient privacy, and we always recommend a professional biopsy for a final medical confirmation.
