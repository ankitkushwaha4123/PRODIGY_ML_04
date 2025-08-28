# Hand Gesture Recognition using CNN (LeapGestRecog Dataset)

This project implements a **hand gesture recognition system** using **deep learning (CNN with transfer learning)**.  
It uses the [LeapGestRecog dataset](https://www.kaggle.com/gti-upm/leapgestrecog) consisting of **200,000 images** across **10 different gesture classes**, collected using a **Leap Motion Controller**.

---

## 📂 Dataset
- **Dataset Name**: LeapGestRecog  
- **Classes (10 Gestures)**:
  1. Palm  
  2. L  
  3. Fist  
  4. Fist Moved  
  5. Thumb  
  6. Index  
  7. OK  
  8. Palm Moved  
  9. C  
  10. Down  

👉 Download here: [LeapGestRecog Dataset on Kaggle](https://www.kaggle.com/gti-upm/leapgestrecog)

---

## 🚀 Features
- Preprocessing pipeline with **TensorFlow & Keras**  
- CNN-based model with **transfer learning (e.g., MobileNetV2 / EfficientNet)**  
- Fine-tuning last layers for improved accuracy  
- Training, validation, and prediction support  
- Achieved **~35%+ accuracy** after fine-tuning (can be improved with more epochs & augmentation)

---

## 📦 Requirements
Install dependencies:
```bash
pip install tensorflow keras opencv-python matplotlib numpy
