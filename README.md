#  Deep Learning-Based Sheep Breed Identification Using VGG16

This project was developed as a major project during my final year (2024–25) using deep learning to identify various sheep breeds based on images. The model was built using **VGG16** with transfer learning and evaluated for accuracy, precision, and F1-score.

 **IEEE Research Paper Published**  
📎 [IJARCCE 2025 Paper DOI](https://doi.org/10.17148/IJARCCE.2025.14xx)

 **Colab Code Link:**  
[Click here to view the full project code in Google Colab](https://colab.research.google.com/drive/1Bfwzg9HzXZS26GscTuUwCYCvPFb9D58Z?usp=drive_link)

---

##  Project Objective

To develop a CNN-based classification model that automatically identifies sheep breeds from image data using transfer learning with VGG16 architecture.

---

##  Tools & Technologies Used

- Python  
- TensorFlow / Keras  
- Google Colab  
- VGG16 Pretrained Model  
- Matplotlib, Seaborn  
- ImageDataGenerator

---

##  Working Process

1. Load and preprocess sheep breed dataset (6 classes).  
2. Use **VGG16** as base model with frozen layers.  
3. Add Dense, Dropout, and Batch Normalization layers.  
4. Train the model and evaluate on test data.  
5. Visualize results with graphs and confusion matrix.

---

##  Dataset Summary

| Detail            | Value            |
|-------------------|------------------|
| Total Images      | 349              |
| Classes           | 6 Sheep Breeds   |
| Train Images      | 291              |
| Validation Images | 33               |
| Test Images       | 25               |

---

##  Model Performance

| Metric             | Value            |
|--------------------|------------------|
| Training Accuracy  | 89.20%           |
| Validation Accuracy| 81.82%           |
| Test Accuracy      | 80.00%           |
| Best F1 Score      | 0.89 (Goat-A_ardy)|

---

##  Features

- Sheep breed classification using images  
- VGG16 + custom classifier head  
- Regularization using Dropout and L2  
- Transfer learning for small datasets  
- Visual analytics of performance

---

##  What I Learned

- How to implement transfer learning with VGG16  
- Fine-tuning CNN layers  
- Optimizing using regularization (Dropout, L2)  
- Image classification workflows  
- Preparing research paper for IEEE journal

---

##  Publication Info

-  **Paper Title**: Deep Learning-Based Sheep Breed Identification Using VGG16 and Architectural Enhancement  
-  **Authors**: Meghana A R, Sneha R L, Navyashri P A, Dr. Ravikiran H K, Priyadharshini L  
-  **Journal**: IJARCCE, Volume 14, Issue X, 2025  
-  **DOI**: [10.17148/IJARCCE.2025.14xx](https://doi.org/10.17148/IJARCCE.2025.14xx)

---

##  Project Info

-  Year: 2024–25  
-  Project Type: Major Project  
-  College: Navkis College of Engineering, Hassan   
-  Team Size: 4

---

## Future Scope

- Deploy model as a mobile app for farmers  
- Expand dataset to improve accuracy  
- Use MobileNet for lightweight version  
- Combine with livestock monitoring system

---

##  Code Files Note

Code is available on Google Colab using the link above. Dataset access and training model weights can be provided upon request for educational purposes.

