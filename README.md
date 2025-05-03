
# Problem Statement
Develop an end-to-end AI model combining EHR, genomic, and imaging features to classify disease progression risk in patients.
Develop a deep learning pipeline that integrates genomic data, medical imaging, and electronic health records to predict disease progression (e.g., Alzheimer's or cancer)

##  Tools & Technologies
- Python, PyTorch, torchvision
- pandas, numpy, matplotlib, scikit-learn
- ResNet for image processing
- Fully connected layers for tabular data
- AI Concepts: Multimodal learning, transformers, CNNs, survival analysis

Combining biological and clinical data modalities, and working with time-series and high-dimensional data.

##  Methodology
- Synthetic datasets were generated to mimic real-world data distributions.
- Separate neural network branches were used for each modality and merged for final classification.
- Trained using categorical cross-entropy and evaluated on accuracy and AUC.

##  Key Results
- Final Accuracy: ~76%
- AUC Score: ~0.81
- Loss curve is visualized and saved as `loss_curve.png`.


##  Output Files
- `loss_curve.png` – Visual graph of training loss
- `executive_summary.txt` – Plaintext report for stakeholders

