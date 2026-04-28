LifeLonger: Continual Disease Classification Replication
Project Focus: Mitigating Catastrophic Forgetting in Medical Imaging using EWC (Elastic Weight Consolidation).

📋 Paper Reference
Title: LifeLonger: A Benchmark for Continual Disease Classification

Authors: Mohammad Mahdi Derakhshani et al. (2022)

Dataset: MedMNIST (12 medical image datasets)

🎯 Project Goal
The goal of this project is to replicate the performance of the EWC algorithm as presented in the "LifeLonger" benchmark. We aim to demonstrate how a model can learn new medical tasks (e.g., organ histology) without losing the ability to classify previous ones (e.g., chest X-rays).

🧬 Biotech & Medical Context (Why this paper?)
I chose this paper because it addresses a critical safety issue in medical AI: Catastrophic Forgetting. In a clinical setting, AI models must be able to update their knowledge with new data from different hospitals or diseases without forgetting previous diagnostic capabilities. Using the MedMNIST collection provides a realistic foundation for testing these lifelong learning systems.

💻 Technical Setup
Language: Python

Framework: PyTorch

Environment: Google Colab

AI Assistance: Full documentation of AI interactions is included in the AI_Logs folder.
