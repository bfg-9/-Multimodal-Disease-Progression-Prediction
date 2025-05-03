
# Multimodal Disease Progression Prediction

## 🧠 Project Overview
This project demonstrates a prototype deep learning pipeline for predicting disease progression using multimodal data: electronic health records (EHR), genomic features, and medical imaging. The model is designed to simulate real-world clinical AI applications such as risk stratification or early intervention strategies for chronic conditions like Alzheimer's or cancer.

## 🎯 Objective
Develop an end-to-end AI model combining EHR, genomic, and imaging features to classify disease progression risk in patients.

## 🛠️ Tools & Technologies
- Python, PyTorch, torchvision
- pandas, numpy, matplotlib, scikit-learn
- ResNet for image processing
- Fully connected layers for tabular data

## 🧪 Methodology
- Synthetic datasets were generated to mimic real-world data distributions.
- Separate neural network branches were used for each modality and merged for final classification.
- Trained using categorical cross-entropy and evaluated on accuracy and AUC.

## 📈 Key Results
- Final Accuracy: ~76%
- AUC Score: ~0.81
- Loss curve is visualized and saved as `loss_curve.png`.

## 📋 Executive Summary
An executive summary is generated post-run in `executive_summary.txt` outlining:
- Business value
- Method
- Key metrics
- Deployment recommendations

## 📦 Installation

```bash
pip install -r requirements.txt
python multimodal_disease_prediction_exec.py
```

## 📊 Output Files
- `loss_curve.png` – Visual graph of training loss
- `executive_summary.txt` – Plaintext report for stakeholders

## 🧠 Author
Sutanuka Nayak
