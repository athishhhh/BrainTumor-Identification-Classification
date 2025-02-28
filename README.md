# BrainTumor-Identification-Classification

Brain tumor classification and detection using deep learning models (**CNN, CNN-LSTM, U-Net**) to analyze MRI scans for **Glioma, Meningioma, Pituitary Tumor, and No Tumor**. This project improves accuracy, speeds up diagnosis, and ensures scalable detection.

---

## Dataset & Preprocessing

- **Dataset Sources:** Figshare, SARTAJ, and Br35H (**7,023 MRI images**)
- **Preprocessing Steps:**  
  - Resizing  
  - Grayscale conversion  
  - Normalization  
  - One-hot encoding  
  - Data splitting  

---

## Model Architectures

-### **1. CNN (Convolutional Neural Network)**
- Extracts spatial features for **static MRI classification**.
- Uses convolutional layers for feature detection and max-pooling for downsampling.
- **Accuracy:** **94.2%** (Best for spatial feature extraction).
  
  ![image alt](https://github.com/athishhhh/BrainTumor-Identification-Classification/blob/5f41719f47fa793f7cdd7334a57cc6a4a68096a7/CNN.webp)

  
### **2. CNN + LSTM (Hybrid Model)**
- Captures **both spatial and temporal dependencies** in MRI sequences.
- CNN extracts spatial features; LSTM processes MRI sequences over time.
- **Accuracy:** **83.08%** (Best for analyzing MRI sequences).
  
### **3. U-Net (Encoder-Decoder Segmentation Model)**
- Designed for **precise tumor segmentation**.
- Encoder extracts features; decoder reconstructs tumor regions with skip connections.
- **Accuracy:** **86.08%** (Best for tumor segmentation).
  
  ![image alt](https://github.com/athishhhh/BrainTumor-Identification-Classification/blob/e4ce502bcbef17db6e3e9567d25d985c971da8ef/u-net.webp)

---

## Training & Evaluation

- **Optimization:** Adam optimizer with categorical cross-entropy loss  
- **Performance Metrics:**  
  - Accuracy  
  - Precision  
  - Recall  
  - F1-score  
  - Confusion Matrix  

---

## Results

| Model      | Accuracy | Key Strength |
|------------|---------|------------------------------|
| **CNN**      | 94.2%   | Best for spatial feature extraction |
| **CNN + LSTM** | 83.08%  | Excels in sequential MRI analysis |
| **U-Net**    | 86.08%  | Best for detailed tumor segmentation |

---

## Conclusion

This project demonstrates the effectiveness of **deep learning** in **brain tumor classification and detection**, with **CNN achieving the highest accuracy** and **U-Net excelling in detailed segmentation**. The approach ensures **scalability and real-time applicability** in medical diagnostics.

---

