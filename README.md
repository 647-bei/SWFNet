# SWFN: A Bio-Inspired Spiking-Wavelet Network for Compressed 360-Degree Video Enhancement


[![Status](https://img.shields.io/badge/Status-Submitted-yellow.svg)]()

> 📢 **Note:** This repository is the official implementation of the paper **"SWFN: A Bio-Inspired Spiking-Wavelet Network for Compressed 360-Degree Video Enhancement"**.
>
> **The full source code, pre-trained weights, and training scripts will be made publicly available immediately upon the acceptance of the paper.**

## 📖 Introduction

**SWFN** is a novel neuromorphic-inspired architecture designed for the restoration of compressed 360-degree videos. By mimicking the **Magnocellular-Parvocellular (M-P)** dual-stream mechanism of the primate visual system, SWFN effectively decouples global structural modeling from fine-grained texture refinement.

### Key Contributions:
* **Bio-Inspired Architecture:** Integrates Spiking Neural Networks (SNNs) with Wavelet transforms to mimic the M-P pathways.
* **Efficiency:** Achieves state-of-the-art performance on 4K/8K datasets with only **1.48M parameters** and **2.32 GFLOPs**.
* **Performance:** Superior restoration of geometric distortions caused by Equirectangular Projection (ERP).

## 🖼️ Model Architecture

The overall architecture of the proposed SWFN framework is shown below:
![model](https://github.com/user-attachments/assets/0acfb710-8856-42bd-aa1e-8b08e6f4f5ce)





