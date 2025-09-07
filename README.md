🐛 Pest Image Classification — Supervised Learning Project
📌 Overview
This project aims to classify pest species from agricultural images using supervised machine learning models. It supports both traditional ML (SVM with HOG features) and deep learning (CNN) pipelines. The goal is to assist farmers and agronomists in identifying pests and recommending targeted interventions.

🧠 Objectives
- Build a supervised model to classify pest species from images
- Compare CNN and SVM performance on the same dataset
- Enable real-time prediction and evaluation
- Lay groundwork for pesticide recommendation logic

📁 Dataset
- Source: Pestopia Dataset on Kaggle
- Classes: 10–132 pest categories (depending on subset used)
- Size: ~55,000 images
- Format: JPEG/PNG images organized by class folders

⚙️ Tech Stack
- Python 3.11
- TensorFlow / Keras
- scikit-learn
- OpenCV
- Matplotlib / Seaborn
- Jupyter Notebook / Kaggle Kernel

🧪 Model Options
✅ CNN (Deep Learning)
- Input: Raw images (128×128×3)
- Architecture: 3 Conv layers + Dense + Dropout
- Output: Softmax classification
- Accuracy: ~90% on validation set (varies by subset)
✅ SVM (Traditional ML)
- Input: HOG features from grayscale images
- Kernel: Linear
- Output: Multiclass classification
- Accuracy: ~75–85% depending on feature quality
