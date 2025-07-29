# 🧠 Kidney Tumor Detection using CNN

This project is a deep learning-based image classification system designed to detect kidney tumors from medical images using a Convolutional Neural Network (CNN) built with TensorFlow and Keras.

---

## 📁 Dataset

- Contains two classes:  
  - **Normal**  
  - **Tumour**
- Images were preprocessed to a fixed size (128x128).
- Directory structure:
  ```
  dataset/
  ├── Normal/
  └── Tumour/
  ```

---

## 🛠️ Technologies Used

- Python
- TensorFlow / Keras
- NumPy
- Matplotlib
- PIL (Python Imaging Library)

---

## 📈 Model Architecture

- Convolutional layers (Conv2D + MaxPooling)
- Flatten and Dense layers
- Dropout to reduce overfitting
- Binary classification output (Normal or Tumor)

---

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/kidney-tumor-detection.git
   ```

2. Create a virtual environment and install dependencies:
   ```bash
   python -m venv kidney_env
   kidney_env\Scripts\activate
   pip install -r requirements.txt
   ```

3. Run the main training script:
   ```bash
   python train_model.py
   ```

4. Predict on new image:
   ```python
   predict_image("path_to_image.jpg")
   ```

---

## 🖼️ Sample Prediction

![Sample Image]![Tumor- (4)](https://github.com/user-attachments/assets/7a3fc6c5-4635-4b9d-8b4b-641eefb726e8)

> **Prediction:** Tumor

---

## 📦 Project Structure

```
Kidney_Tumor_Detection/
├── dataset/
├── train_model.py
├── model.h5
├── predict_image.py
├── requirements.txt
└── README.md
```

---

## ✅ Results

- Accuracy: ~XX% *(Fill this based on your actual result)*
- Loss: ~XX
- Works well on validation/test data

---

## 📚 Future Improvements

- Add more data for better generalization
- Convert to web app with Streamlit
- Integrate with mobile app for easy diagnosis

---
