Emotion Detection using Large Language Models (LLMs)
Overview
This project investigates the capabilities of Large Language Models (LLMs) — specifically BERT, XLNet, and GPT-2 — for emotion classification from text data. 
It explores fine-tuning, hyperparameter optimization, class balancing through data augmentation, and evaluates model performance with standard NLP metrics.

Features
Fine-tuning of BERT, XLNet, and GPT-2 models for multi-class emotion detection.

Data augmentation of minority classes using GPT-2-based text generation.

Hyperparameter optimization with Optuna (learning rate, weight decay, warmup ratio).

Early stopping to prevent overfitting.

Automatic evaluation (Accuracy, F1-Macro, Confusion Matrices).

Balanced dataset creation based on original emotion distribution.

Visualization of model performances.

Training on GPU and compatibility with HPC clusters.

Comprehensive reproducibility: saved models, generated outputs, tuning logs.

Requirements
pip install transformers datasets accelerate optuna nltk matplotlib scikit-learn seaborn pandas torch

