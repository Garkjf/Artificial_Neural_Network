#Artificial Neural Network Project  
### Online Shopper Purchase Intention Prediction
---
## Presentation Video
Due to repository upload limitations, the video is hosted externally in One Drive:

 [Watch Presentation Video Here](https://livecoventryac-my.sharepoint.com/:v:/g/personal/garkj_uni_coventry_ac_uk/IQBV33n5fVl8SJuSXMz0bV3jAQWn0Lwrlr576_RDX61hBpA)

---

## Project Overview
This project focuses on predicting whether an online shopping session will result in a purchase using Artificial Neural Networks (ANN). The dataset used is the **Online Shoppers Purchasing Intention Dataset**, which contains user session data from an e-commerce platform.

The project compares two approaches:
- **Part A:** Human-guided model design  
- **Part B:** GenAI-assisted model optimisation  

The goal is not only to build accurate models but also to analyse performance under class imbalance and evaluate the impact of AI-assisted development.

---

## Dataset
- **Source:** UCI Machine Learning Repository  
- **Size:** 12,330 sessions  
- **Features:** 18  
- **Target Variable:** `Revenue` (0 = No Purchase, 1 = Purchase)  

---

## Tools & Libraries
- Python (Jupyter Notebook)
- Scikit-learn
- TensorFlow / Keras
- Pandas & NumPy
- Matplotlib & Seaborn
---

##  Models Implemented

### Part A – Human-Guided Models
- Multi-Layer Perceptron (MLP)
- Recurrent Neural Network (SimpleRNN)

### Part B – GenAI-Assisted Models
- Optimised MLP (deeper architecture, regularisation)
- LSTM-based RNN (improved sequence modelling)

---
## Result
- Part A – Human-Guided Models:The baseline MLP and RNN achieved good overall accuracy, but struggled to identify the minority purchase class, with relatively low recall and F1-score.
- Part B – GenAI-Assisted Models:The GenAI-optimised models improved minority-class performance, with higher recall and average precision, especially using LSTM and deeper MLP architectures.
  
---
