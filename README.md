# Regularization and Robustness Evaluation Using SHAP

This repository contains a Python script that evaluates the effectiveness of various regularization techniques on the robustness of a simple neural network trained on the MNIST dataset. The primary focus is on using SHAP (SHapley Additive exPlanations) and other attribution methods like DeepLIFT and GradientSHAP to improve model robustness against adversarial attacks.

## Overview

The project aims to assess how regularization using attribution methods can enhance a model's robustness. The script performs the following:

- **Training with Regularization**: Implements training routines that incorporate SHAP, DeepLIFT, and GradientSHAP-based regularization.
- **Robustness Evaluation**: Evaluates the model's robustness by measuring the correlation between SHAP values of clean and adversarial examples.
- **Adversarial Accuracy**: Tests the model's performance against adversarial examples generated using the FGSM (Fast Gradient Sign Method) attack.

## Key Features

- **Comparison of Regularization Techniques**: Analyzes and compares the impact of SHAP, DeepLIFT, and GradientSHAP-based regularization on model robustness.
- **Robustness Metrics**: Uses Pearson correlation and adversarial accuracy as metrics to evaluate the effectiveness of different regularization methods.
- **Adversarial Training**: Explores the effectiveness of adversarial training using FGSM to further enhance model robustness.
