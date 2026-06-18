# bug-free-journey

# 🎧 WMCodec-M2: Robust Audio Watermarking Red-Teaming & Defense System

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/YOUR_GITHUB_USERNAME/YOUR_REPO_NAME/blob/main/WMCodec_Evaluation.ipynb)
[![Python 3.12](https://img.shields.io/badge/python-3.12-blue.svg)](https://www.python.org/)
[![PyTorch 2.8](https://img.shields.io/badge/pytorch-2.8%2Bcu126-orange.svg)](https://pytorch.org/)
[![License MIT](https://img.shields.io/badge/license-MIT-green.svg)](https://opensource.org/licenses/MIT)

> **FIT5230 Milestone 3 Project - Champions of the World**
> A comprehensive security evaluation, advanced adversarial attack, and test-time defense framework for deep-learning-based Audio Watermarking (`WMCodec`).

---

## 🌟 Overview

This project builds a fully functional verification and security testing pipeline for the **WMCodec** audio watermarking system. Going beyond standard robustness tests, we implement state-of-the-art **Adversarial Red-Teaming Techniques** to systematically blindside decoders, balanced with adaptive **Test-Time Augmentation (TTA) and Notch-Filtering Defenses** to shield watermarks against aggressive distortions.

### 🛠️ Key Systems & Contributions
1. **End-to-End Evaluation Pipeline**: Auto-preprocessing (24kHz mono resampling and peak normalization), watermark embedding inference, and synchronized bit alignment.
2. **RHDE-Inspired Adversarial Attacker**: Combines **Band-Limited Audio "Stickers" (bursts/chirps)**, **Differential Evolution (DE) global search**, and **Projected Gradient Descent (PGD) optimization** to destroy watermarks under strict psychoacoustic constraints.
3. **Adaptive Test-Time Defense (Light Defense)**: Implements test-time augmentation (TTA) with soft-logits voting and a **Confidence-Driven Adaptive Notch Filter** to successfully recover watermarks from heavily corrupted channels.
4. **Deception & Misdirection Mechanics (Bonus Marks)**: Features covert tactical functions to mislead adversarial attribution and mitigate red-teaming bypasses.

---

## 📊 System Architecture & Workflow
