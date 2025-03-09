# AI-Powered-Skin-Cancer-Detection
📌 Project Overview :
This project focuses on developing an AI-based skin cancer detection system using deep learning techniques. The system is designed to analyze dermoscopic images and classify them as benign or malignant with high accuracy. The goal is to assist dermatologists and general users in early detection, improving patient outcomes, and making skin cancer diagnosis more accessible, particularly in resource-limited settings.

🚀 Features :
1) Automated Diagnosis: Uses deep learning to classify skin lesions.
2) Real-time Classification: Provides instant results upon image upload. 
3) Vision Transformer (ViT) Model: A state-of-the-art transformer-based architecture for image analysis.
4) Explainability with Grad-CAM: Highlights critical areas in an image for better interpretability.
5) User-Friendly Interface: Accessible via a web or mobile application.
6) Cloud Deployment: Ensures scalability and reliability.

📊 Technologies Used
1) Frontend: React, HTML/CSS
2) Backend: Flask
3) AI Model: Vision Transformer (ViT) using TensorFlow/PyTorch
4) Preprocessing: OpenCV, PIL, Scikit-Image
5) Deployment: Cloud-based hosting

🔍 How It Works
1) User Uploads an Image: A dermoscopic image of the skin lesion is uploaded.
2) Image Preprocessing: The image is resized, normalized, and cleaned.
3) AI Model Prediction: The ViT model classifies the lesion as normal, benign, or malignant.
4) Results Displayed: The result is presented along with a confidence score and heatmap visualization (Grad-CAM).
