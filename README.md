# 👨‍💻 Gender Detection using CNN 🧠📸

This repository presents a deep learning approach for **gender classification** using **Convolutional Neural Networks (CNNs)**.  
The project covers **data preprocessing, model training, and evaluation** with Python and popular ML libraries. 🚀

---

## 📂 Dataset

We use the **[Gender Classification Dataset](https://www.kaggle.com/datasets/cashutosh/gender-classification-dataset)** from Kaggle.  
It contains two categories of images:

- 👨🏻 **Male**  
- 👩🏻 **Female**

Images are divided into:
- 📁 `Training/` — used for model training  
- 📁 `Validation/` — used for evaluation  

---

## 🛠️ Libraries & Purpose

-  **NumPy** → Efficient array and matrix operations  
-  **Pandas** → Dataset handling and preprocessing support  
-  **Matplotlib** → Visualization of images + training curves  
-  **OpenCV (cv2)** → Image loading, resizing, color conversion  
-  **TensorFlow / Keras** → Building and training the CNN model  
-  **Warnings** → Cleaner logs (ignore runtime warnings)  

---

## ⚙️ Methodology

1. 🖼️ **Data Preprocessing**
   - Resize images to **128×128**
   - Convert to **RGB**
   - Normalize pixel values  

2. 🧩 **Model Architecture**
   -  Convolutional Layers (Conv2D) → feature extraction  
   -  MaxPooling → dimensionality reduction  
   -  Flatten → vector representation  
   -  Dense Layers → classification  
   -  Sigmoid → Male/Female prediction  

3. 📚 **Training**
   - Optimizer:  Adam  
   - Loss:  Binary_crossentropy  
   - Metric:  Accuracy  

4. 📊 **Evaluation**
   - Accuracy & loss measured on validation set  
   -  Learning curves plotted  

---

## 🏆 Results

-  High accuracy on validation data  
-  Training/Validation curves show stable learning  

---

## ▶️ Usage

1. ⬇️ Clone the repo:
   ```bash
   git clone https://github.com/your-username/gender-detection-cnn.git
   cd gender-detection-cnn
