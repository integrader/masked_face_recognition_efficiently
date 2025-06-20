#  Masked Face Recognition System using FaceNet and SVM

<img src="C:\Users\Abhishek Kumar\Downloads\img.jpg" alt="Masked Face Recognition Demo" width="600"/>


This project is a robust **Masked Face Recognition System** built using **FaceNet** for embedding extraction and **SVM (Support Vector Machine)** for classification. It addresses the challenges of recognizing faces with masks, which became a critical problem during the COVID-19 pandemic.

##  Project Highlights

-  **Accuracy Achieved**:
  - **Masked-only training**: 97.66%
  - **Combined training (masked + unmasked)**: 97.29%
  - **Unmasked-only training**: 86.67%
-  **Embedding Model**: Pre-trained FaceNet (128D embeddings)
-  **Face Detection**: MTCNN for face alignment and cropping
-  **Classifier**: Multi-class SVM with RBF kernel
-  **Dataset**: 105 classes (celebrities) with 150 unmasked images per class  
  - Masked dataset created using [MaskTheFace](https://github.com/aqeelanwar/MaskTheFace)

---



## 🛠️ Technologies Used

- Python
- FaceNet (Keras)
- MTCNN
- Scikit-learn
- NumPy, Pandas
- Matplotlib (for visualization)

---

##  Training Approaches Compared

| Training Data        | Accuracy (%) |
|----------------------|--------------|
| Unmasked Only        | 86.67%       |
| Masked Only          | 97.66%       |
| Masked + Unmasked    | 97.29%       |

---

##  Key Takeaways

- **Masked training data** is crucial for achieving high recognition accuracy in masked scenarios.
- **Combining both masked and unmasked data** provides good generalization but slightly lower accuracy than masked-only training.
- Using **FaceNet embeddings + SVM** is highly effective for masked face classification.

---

##  Future Improvements

- Real-time webcam-based recognition
- Support for video-based face recognition
- Model deployment with Streamlit or Flask
- Optimize using ONNX for faster inference

---

##  License

This project is for academic and research purposes.

---

##  Contact

**Abhishek Kumar**  
📧 astreithm11@gmail.com  
🔗 [LinkedIn](https://www.linkedin.com/in/abhishek-kumar-86b317274) | [GitHub](https://github.com/integrader)


#   m a s k e d _ f a c e _ r e c o g n i t i o n _ e f f i c i e n t l y 
 
 #   m a s k e d _ f a c e _ r e c o g n i t i o n _ e f f i c i e n t l y 
 
 