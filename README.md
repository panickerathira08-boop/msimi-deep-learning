# Classification of Mental Stress-Induced Myocardial Ischemia using Multimodal Deep Learning

## Overview
This project presents a multimodal deep learning framework for classification of Mental Stress-Induced Myocardial Ischemia (MSIMI) using ECG-derived datasets collected across Rest, Stress, and Recovery cardiac stages.

The framework combines nonlinear signal analysis, recurrence plot imaging, contrastive learning, attention-based architectures, and multimodal fusion strategies to identify clinically relevant cardiac stress patterns from physiological signals.

The study focuses on improving automated cardiovascular risk prediction using deep learning and healthcare-oriented AI workflows.

---

# Problem Statement
Mental Stress-Induced Myocardial Ischemia (MSIMI) is a clinically significant cardiovascular condition that can occur even in the absence of physical stress symptoms. Early identification of MSIMI remains challenging due to subtle physiological variations and complex nonlinear ECG patterns.

This project aims to:
- Analyze ECG-derived multimodal signals
- Extract nonlinear and image-based representations
- Build robust deep learning architectures
- Improve automated MSIMI classification performance
- Explore multimodal healthcare AI techniques

---

# Objectives
- Develop multimodal deep learning architectures for MSIMI detection
- Transform ECG signals into recurrence plot image representations
- Extract nonlinear biomarkers using Higuchi Fractal Dimension (HFD)
- Apply contrastive learning using SimCLR pretraining
- Build fusion-based healthcare AI models
- Evaluate clinically relevant classification performance

---

# Dataset Information

## Dataset
- Public ECG-based multimodal dataset
- 119 female subjects
- Multiple cardiac stress stages included

## Cardiac Stages
- Rest
- Stress
- Recovery

## Data Modalities
- ECG signals
- Recurrence Plot Images
- Nonlinear Fractal Features

---

# Methodology

## 1. ECG Signal Preprocessing
The ECG signals were processed using:
- Noise reduction
- Signal normalization
- Segmentation
- Feature extraction
- Time-series standardization

---

## 2. Recurrence Plot (RP) Generation
Recurrence plots were generated from ECG signals to capture nonlinear temporal dynamics and hidden physiological structures.

### Purpose
- Convert ECG signals into image representations
- Enable CNN-based feature learning
- Capture nonlinear cardiac patterns

---

## 3. Higuchi Fractal Dimension (HFD)
HFD analysis was used to quantify signal complexity and nonlinear behavior in ECG signals.

### Benefits
- Captures signal irregularity
- Represents physiological complexity
- Enhances multimodal learning

---

## 4. Contrastive Learning using SimCLR
Self-supervised contrastive learning was implemented using SimCLR pretraining.

### Advantages
- Improved representation learning
- Better feature generalization
- Reduced dependency on labeled data
- Enhanced multimodal embeddings

---

# Deep Learning Architectures

The project includes implementation and evaluation of multiple architectures:

## CNN Architectures
- EfficientNetB0
- EfficientNetB0 + SimCLR Pretraining
- MobileNet Dual-Stream Architecture

## Attention-Based Models
- HFD Attention MLP

## Fusion Architectures
- Gated Fusion Models
- Fusion-based Multimodal Architectures

---

# Multimodal Fusion Strategy
The framework integrates:
- Image-based features
- Nonlinear fractal features
- Deep neural representations

This fusion-based strategy improves classification robustness and captures complementary physiological information.

---

# Evaluation Metrics

Model performance was evaluated using:

- Accuracy
- Precision
- Recall
- F1-Score
- AUC Score
- Confusion Matrix Analysis

---

# Results

## Best Performing Model
### Fusion-2 Architecture
- AUC Score: 0.69

## Observations
- Fusion architectures outperformed standalone models
- SimCLR pretraining improved feature representation quality
- Multimodal integration improved classification stability
- Nonlinear feature extraction enhanced predictive performance

---

# Technologies Used

## Programming & Frameworks
- Python
- TensorFlow
- Keras
- PyTorch

## Libraries
- OpenCV
- NumPy
- Pandas
- Scikit-learn
- Matplotlib

## AI & Healthcare Technologies
- Deep Learning
- Medical AI
- Contrastive Learning
- Multimodal AI
- Explainable AI

---

# Repository Structure

```bash
├── data_preprocessing/
├── recurrence_plot_generation/
├── hfd_feature_extraction/
├── simclr_pretraining/
├── model_training/
├── fusion_models/
├── evaluation/
├── notebooks/
├── results/
└── saved_models/
```

---

# Research Contributions
- Developed a multimodal AI framework for MSIMI classification
- Combined nonlinear signal analysis with deep learning workflows
- Applied contrastive learning for healthcare representation learning
- Built fusion-based architectures for improved predictive performance
- Evaluated clinically relevant cardiovascular classification metrics

---

# Applications
- Cardiovascular risk prediction
- Stress-induced ischemia detection
- Healthcare AI research
- ECG-based predictive analytics
- Medical signal processing
- Clinical decision support systems

---

# Future Improvements
- Transformer-based ECG architectures
- Explainable AI visualization modules
- Real-time ECG monitoring systems
- Clinical deployment pipelines
- Larger multimodal datasets
- Edge AI healthcare integration

---

# Note
Due to the modular research workflow and extensive experimental setup, the complete implementation consists of multiple Jupyter notebooks and supporting files.

Additional notebooks, trained models, experimental configurations, preprocessing workflows, and supplementary code files can be shared upon request for academic, research, or recruitment purposes.

---

# Author

## Athira Panicker
M.Tech Data Science  
Healthcare AI | Deep Learning | Clinical Analytics | Generative AI

### Connect
- GitHub: https://github.com/panickerathira08-boop
- LinkedIn: https://www.linkedin.com/in/athira-p-1408ap

---
