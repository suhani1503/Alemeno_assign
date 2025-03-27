# Alemeno_assign

📌 QR Code Authentication using Machine Learning & Deep Learning
🔍 Overview
This project implements a QR Code Authentication System using both traditional machine learning (feature engineering) and deep learning (CNNs) to distinguish between First Print and Second Print QR codes.

📁 Dataset
The dataset consists of images categorized into:
✅ First Print (original QR codes)
✅ Second Print (reprinted QR codes)

Images are loaded, preprocessed, and analyzed to extract key features for classification.

🛠️ Features & Methodology
1️⃣ Feature Engineering (Traditional ML Approach)
📌 Extracts image-based features using:

Laplacian Variance → Measures sharpness & print quality.

Sobel X & Y → Captures edge distortions.

2️⃣ Deep Learning (CNN Approach)
🚀 A Convolutional Neural Network (CNN) is trained on images for classification. The model consists of:

Convolutional Layers → Learn patterns in QR codes.

MaxPooling Layers → Reduce dimensions & preserve features.

Fully Connected Layers → Make final predictions.

📊 Model Performance
✅ Accuracy: 97.5%
✅ Precision (Class 1): 95%
✅ Recall (Class 1): 100%
✅ Confusion Matrix:

The model effectively classifies QR codes with minimal false positives and zero false negatives.

📝 Future Improvements
🔄 Expand Dataset → Improve generalization on diverse QR codes.

🧠 Experiment with Transfer Learning → Pretrained models like ResNet.

📲 Deploy as a Web API → Flask or FastAPI for real-time QR authentication.

