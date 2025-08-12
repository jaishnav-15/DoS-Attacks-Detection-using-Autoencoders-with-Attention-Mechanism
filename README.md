# DoS-Attacks-Detection-using-Autoencoders-with-Attention-Mechanism
Real-time DoS attack detection system using a self-supervised, attention-based autoencoder model, deployed with FastAPI, achieving 97.60% accuracy.

This project implements a real-time system for detecting Denial of Service (DoS) attacks using a self-supervised, attention-based autoencoder. Trained exclusively on normal network traffic from the NSL-KDD dataset , the model learns to identify anomalous deviations with high precision. It leverages a FastAPI backend for scalable, low-latency inference, making it highly suitable for deployment in live network environments. The core idea is to flag any traffic that the model cannot reconstruct accurately as a potential threat.


# Key Features

- Self-Supervised Learning: Detects novel threats without needing labeled attack data, learning only from normal behavior.
- Attention Mechanism: Dynamically focuses on the most relevant traffic features, significantly improving detection accuracy over standard autoencoders.
- Real-Time Inference: Deployed with a high-performance FastAPI server for immediate, low-latency attack detection.

# High-Performance Results
The model achieves 97.60% accuracy and a 98.55% ROC-AUC score, outperforming traditional classifiers like SVM, XGBoost, and Logistic Regression.

# IEEE Publication
Acccess this paper - [Published on IEEE](https://www.researchgate.net/publication/394187505_Self-Supervised_Anomaly_Detection_for_DoS_Attacks_Using_Autoencoders_with_Attention_Mechanism_and_Real-Time_Detection)

# Cite Us
Jayshnav S, Archana Mahendran, and Jeyasekar A, “Self-Supervised Anomaly Detection for DoS Attacks Using Autoencoders with Attention Mechanism and Real-Time Detection,” 2022 4th International Conference on Inventive Research in Computing Applications (ICIRCA), pp. 465–471, Jun. 2025, [doi: https://doi.org/10.1109/icirca65293.2025.11089924]
