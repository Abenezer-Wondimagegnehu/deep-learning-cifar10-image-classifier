# 🚀 CIFAR-10 Image Classifier — Engineering the Champion
Production-ready CIFAR-10 image classification pipeline using ResNet50 transfer learning. Implements iterative fine-tuning, strategic data augmentation, and performance-focused engineering. Achieved 72.1% validation accuracy (+10.5pp over baseline) with deployment-grade artifacts and inference pipeline.

## 🧠 Project Overview
This project tackles the structural feature recognition challenge in CIFAR-10 — a key weakness of baseline convolutional models on geometric test cases (e.g., forward-facing or symmetric objects).
Through progressive optimization and diagnosis, the "Champion" model achieved 93.2% confidence on previously misclassified structural features.

### Key Highlights:

Final model accuracy: 72.11%

Structural recognition accuracy: 93.2%

Overcame the 70% saturation barrier through advanced augmentation and fine-tuning

### 🛠️ Technical Stack
Core: TensorFlow · Keras · NumPy · Pandas

Base Model: ResNet50 (transfer learning)

Architecture: Custom Global Average Pooling head + Dropout regularization

Training Strategy: Progressive layer unfreezing, ReduceLROnPlateau & EarlyStopping callbacks

Diagnostics: Confusion matrix–driven analysis and iterative validation

### 📊 Project Pipeline
Baseline Analysis – Identified weak geometric class performance

Error Diagnosis – Examined confusion matrices for structural insights

Data Augmentation Strategy – Introduced real-time transformations for feature invariance

Champion Model Refinement – Fine-tuned architecture for production-level reliability

## Project Presentation

This project was presented at **MSIT (Master School Institute of Technology)**.

You can view the full presentation here:

[![View Presentation](https://img.shields.io/badge/View-Presentation-blue)](https://docs.google.com/presentation/d/1Z5pO_Joogvnp3tDzZQIA6937rhDPM79N/edit?usp=sharing&ouid=106128353566779902680&rtpof=true&sd=true)

The presentation covers:

- Model architecture (ResNet50 transfer learning)
- Baseline performance analysis
- Error diagnosis using confusion matrices
- Data augmentation strategy
- Training improvements
- Final model performance (72.1% accuracy)

## 📁 Repository Structure

```
deep-learning-cifar10-image-classifier
│
├── Deep_learning.ipynb       # Full training, fine-tuning, and evaluation logic
├── presentation.pptx          # Case study presentation (MSIT)
├── README.md                  # Project documentation
└── LICENSE                    # License information
```
