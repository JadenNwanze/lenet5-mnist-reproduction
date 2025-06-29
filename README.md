# LeNet-5: Convolutional Neural Network for Handwritten Digit Recognition

##  Project Summary

This project is a complete implementation a deep learning architecture higlighted in the research paper on **LeNet-5**, originally proposed by **Yann LeCun et al.** in his paper:

> *Gradient-Based Learning Applied to Document Recognition* (LeCun et al., 1998)

The model was applied to the **MNIST dataset** for handwritten digit classification. This project replicates the original architecture for educational reasons of study.

---

##  Research Motivation

The LeNet-5 architecture is historically significant, and it laid the foundation for modern CNNs and application of deep learning in computer vision. I chose to implement this architecture from scratch to:

- Understand the role of convolution, subsampling, and dense layers in feature extraction  
- Reinforce my theoretical and practical understanding of CNNs  
---

##  Tools & Libraries utilized:

- Python 3  
- NumPy & Matplotlib
- TensorFlow  
-pandas

---

##  Architecture Overview

| Layer Type      | Parameters           | Output Size |
|----------------|----------------------|-------------|
| Input          | 32×32 grayscale      | 32×32       |
| Conv1          | 6×5×5 kernel, stride 1| 28×28×6     |
| Subsampling1   | AvgPool, 2×2         | 14×14×6     |
| Conv2          | 16×5×5 kernel        | 10×10×16    |
| Subsampling2   | AvgPool, 2×2         | 5×5×16      |
| Fully Connected| -                    | 120         |
| FC Layer       | -                    | 84          |
| Output         | Softmax              | 10 classes  |

This is a concise tabulated summary of the architectural framework highligted in the research paper for replication of stated results.

---

## Dataset & Results

- **Dataset**: MNIST (The data that was used has already be partioned into training and tesing categories)  
- **Accuracy**: ~98.7% from own implementation


---

---
##  References

- LeCun, Y., Bottou, L., Bengio, Y., & Haffner, P. (1998). *Gradient-based learning applied to document recognition.* Proceedings of the IEEE.
- [LeNet-5 Paper PDF](http://yann.lecun.com/exdb/publis/pdf/lecun-01a.pdf)

---

## 🔗 Related Projects

- **Credit Card Fraud Detection System (CCFDS)**  
  A machine learning web app that detects fraudulent financial transactions using ensemble models (Logistic Regression, Random Forest, XGBoost) and SHAP for interpretability.  
   [Live Demo](https://creditcarddetectionsystem-egseuj4mjysbwzs6benygd.streamlit.app/)  
   [GitHub Repository](https://github.com/JadenNwanze/Credit_card_detection_system)



