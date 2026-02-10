# Emotion Recognition of Golden Retriever Dogs Using Deep Learning

This repository contains the complete project for recognizing emotional states of Golden Retriever dogs using deep learning and computer vision techniques.

It supports:
- dataset preparation  
- model training and evaluation  
- research paper + results

---

## Repository Contents

| File | Description |
|------|-------------|
| `Emotion_Recognition_of_Golden_Retriever_Dogs_Code.ipynb` | Core Jupyter notebook with model training & evaluation |
| `Dog_Emotion_Table.ipynb` | Notebook for dataset analysis / performance table |
| `Emotion_Recognition_of_Golden_Retriever_Using_Deep_Learning_Research Paper.pdf` | Full research paper |
| `ICCoSD Paper.pdf` | Conference version of the paper |
| `README.md` | This file |
| `Dog Emotion PPT.pptx` | Presentation slides |

---

## Project Overview

Emotion recognition in dogs is an emerging area of computer vision that aims to understand animal emotional states using visual cues such as facial and body expressions.

This project focuses on classifying images of Golden Retriever dogs into different emotional categories using deep learning models.

---

## Dataset

The dataset used in this project is publicly available on Kaggle:

 https://www.kaggle.com/datasets/adharasaniveekshitha/golden-retriever-emotion-recognition-dataset

Structure:
```
dataset/
 ├── happy/
 ├── sad/
 ├── angry/
```

---

## Models and Methods

The main notebook includes:
- data loading & preprocessing  
- neural network training  
- evaluation & visualization  
- class-wise performance  
- accuracy results

You can run experiments using frameworks like PyTorch or TensorFlow.

---

## Running the Code

1. Clone the repository
```sh
git clone https://github.com/VeekshithaAdharasani/Emotion-Recognition-of-Golden-Retriever-Dogs-Using-Deep-Learning.git
cd Emotion-Recognition-of-Golden-Retriever-Dogs-Using-Deep-Learning
```

2. Open and run the notebooks in Jupyter or Colab:
```sh
jupyter notebook Emotion_Recognition_of_Golden_Retriever_Dogs_Code.ipynb
```

---

## Results

| Model | Accuracy | Precision | Recall | F1 Score |
|---------|-----------|-----------|-----------|-----------|
| CNN+RNN | 81.67% | 33.05% | 32.78% | 32.52% |
| CNN | 82.78% | 83.95% | 82.78% | 82.38% |
| MobileNetV2 | 83.89% | 82.24% | 82.22% | 82.16% |
| **CNN+LSTM (Proposed Model)** | **86.81%** | **87.28%** | **86.81%** | **86.79%** |

The proposed CNN+LSTM hybrid model achieved the highest performance across all metrics.

## Proposed Model Evaluation (CNN+LSTM)

| Metric | Value |
|-----------|-----------|
| Accuracy | 86.81% |
| Precision | 87.28% |
| Recall | 86.81% |
| F1 Score | 86.79% |

The proposed CNN+LSTM hybrid architecture achieved the best overall performance among all evaluated models.


---

## Research Paper

**Emotion Recognition of Golden Retriever Using Deep Learning**  
Presented at the 2025 International Conference on Communication and Smart Devices (ICCoSD), IEEE.

---

## Cite This Work

If you use this dataset or code, please cite:

Chintala, S., Acharya, D. S., Adharasani, V., & Shireen, R. (2025, July).  
*Emotion Recognition of Golden Retriever Using Deep Learning.*  
In 2025 International Conference on Communication and Smart Devices (ICCoSD), Vol. 1, pp. 1–5. IEEE.

---

##  Author

Adharasani Veekshitha  
GitHub: https://github.com/VeekshithaAdharasani  
Kaggle: https://www.kaggle.com/datasets/adharasaniveekshitha/golden-retriever-emotion-recognition-dataset
Google Scholar: https://scholar.google.com/citations?user=D9pPL58AAAAJ&hl=en

---
## Co-Authors 
- Sridhar Chintala
- Deep Shekhar Acharya
- Rida Shireen
