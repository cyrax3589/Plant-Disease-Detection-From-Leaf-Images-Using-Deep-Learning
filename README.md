# Plant Disease Detection From Leaf Images Using Deep Learning

## Overview
This project focuses on detecting plant diseases from leaf images using a Convolutional Neural Network with transfer learning (MobileNetV2). The system is capable of classifying multiple plant diseases and healthy leaves with high accuracy.

The project includes:
- Dataset preprocessing and augmentation
- Model training using transfer learning
- Evaluation using multiple metrics
- A Streamlit-based web application for real-time predictions

---

## Features
- Image classification using MobileNetV2
- High accuracy with transfer learning
- Data augmentation to prevent overfitting
- Confusion matrix and classification report
- Single image prediction with confidence score
- Streamlit web interface for user interaction

---

## Dataset
The dataset used is the PlantVillage dataset, containing images of plant leaves categorized into different diseases and healthy classes.

```
https://www.kaggle.com/datasets/emmarex/plantdisease
```

---

## Model Details
- Base Model: MobileNetV2 (pretrained on ImageNet)
- Input Size: 224x224
- Loss Function: Categorical Crossentropy
- Optimizer: Adam
- Fine-tuning applied on top layers

---

## Evaluation Metrics
The model is evaluated using:
- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix

---

## Future Improvements
- Add Grad-CAM for model interpretability
- Improve UI design
- Deploy the application online
- Expand dataset for more plant species