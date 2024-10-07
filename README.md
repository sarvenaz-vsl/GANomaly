# GANomaly: Anomaly Detection on TUH EEG Dataset

This project involves developing and training a Generative Adversarial Network (GAN) for detecting anomalies in the TUH EEG dataset. By leveraging adversarial training techniques, the GAN learns to identify outlier patterns in EEG signals, which can be crucial for identifying abnormal brain activity.

## Project Overview

- **Objective**: Implement a GAN-based architecture to detect anomalies in EEG data using unsupervised learning.
- **Dataset**: TUH EEG dataset, a widely used dataset for brain activity analysis.
- **Approach**: 
  - A GAN is trained to generate synthetic "normal" EEG data, while the discriminator helps the model learn to differentiate between normal and anomalous EEG patterns.
  - The adversarial training process enhances the GAN's ability to identify outlier patterns that deviate from the learned normal distributions.
- **Outcome**: Achieved robust anomaly detection capabilities, helping to highlight unusual brain activity in EEG signals.
  
## Tools & Libraries

- **Python**
- **TensorFlow/Keras**
- **NumPy, Pandas**
- **Matplotlib**

## Key Features

- **Unsupervised Learning**: Utilizes unsupervised learning techniques, which are particularly effective in anomaly detection without requiring labeled data.
- **GAN Architecture**: The model leverages the power of GANs (Generative Adversarial Networks) for anomaly detection by generating data that mimics normal EEG patterns.
- **Adversarial Training**: Adversarial training helps refine the model’s ability to detect subtle anomalies in high-dimensional EEG data.
