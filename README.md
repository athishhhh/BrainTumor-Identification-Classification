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

- **CNN:** Extracts spatial features for static MRI classification  
- **CNN + LSTM:** Captures spatial and temporal dependencies for sequence analysis  
- **U-Net:** Uses an encoder-decoder structure for enhanced tumor segmentation  

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

