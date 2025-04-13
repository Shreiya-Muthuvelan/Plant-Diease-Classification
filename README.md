
# 🌿 Plant Disease Classification (Binary Classification)

This project is a binary image classification model built using deep learning to distinguish between **healthy** and **diseased** plant leaves. It leverages a neural network to analyze image features and predict the presence of disease with high accuracy. 

---

## 📌 Features
- Binary classification of plant leaf images.
- Lightweight neural network architecture.
- Easy to scale to multiclass classification if needed.

---

## 🔄 ML Workflow

1. **Data Collection:**  
   Dataset sourced from the [PlantVillage dataset](https://www.kaggle.com/datasets/emmarex/plantdisease)

2. **Preprocessing:**
   - Images organized into `healthy` and `diseased` categories.
   - Resized all images to `128x128` for uniform input size.
   - Normalized pixel values using `ImageDataGenerator`.

3. **Model Architecture (Neural Network):**
   - Input: Flattened image data (`128x128x3`)
   - Dense hidden layer with ReLU activation.
   - Dropout for regularization.
   - Output layer with Sigmoid activation for binary classification.

4. **Model Training:**
   - 80-20 training-validation split.
   - Optimizer: Adam  
   - Loss Function: Binary Crossentropy  
   - Evaluation Metric: Accuracy

5. **Model Evaluation:**
   - Achieved an accuracy of **~85%** on validation data.

---

## 🛠️ Technologies Used
- Python 
- TensorFlow / Keras  
- Pandas, NumPy  
- Matplotlib  
- Google Colab  

---
## 👩‍💻 Author

**Shreiya**  
2nd Year CSE Student | ML & Generative AI Enthusiast  
📍 BITS Pilani Dubai Campus  
🔗 [LinkedIn](https://www.linkedin.com/in/shreiyamuthuvelan)

---
