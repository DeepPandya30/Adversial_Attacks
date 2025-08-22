# Adversial_Attacks
🚀 FGSM and PGD Attacks on CIFAR-10 Models
📌 Project Overview
This project explores adversarial attacks on deep learning models using Fast Gradient Sign Method (FGSM) and Projected Gradient Descent (PGD).
A baseline CNN trained on CIFAR-10 achieved 82% accuracy but was highly vulnerable to attacks.
Targeted attacks were performed to force misclassification (e.g., dog → bird).
An improved ResNet with data augmentation achieved 95% accuracy and showed stronger robustness against adversarial examples.

🧩 Key Features
Implementation of FGSM and PGD attacks.
Targeted adversarial misclassification experiments (e.g., dog → bird, airplane → horse).
Performance comparison between CNN baseline and ResNet + augmentation.
Visualization of adversarial examples and misclassification rates.

📊 Results
CNN Baseline (No augmentation):
Accuracy: 82%
FGSM targeted success (dog → bird): 78.2%
PGD targeted success (dog → bird): 100%
ResNet + Data Augmentation:
Accuracy: 95%
FGSM attack on airplane → horse: 3.3% targeted success
PGD attack on airplane → horse: 59.5% targeted success

⚙️ Tech Stack

Python
PyTorch
CIFAR-10 Dataset

