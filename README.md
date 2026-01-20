# SWFNet: A Spiking-Wavelet Fusion Network for Quality Enhancement of VVC-Compressed 360-Degree Video

[![Status](https://img.shields.io/badge/Status-Submitted-yellow.svg)]()

> 📢 **Note:** This repository is the official implementation of the paper **"SWFNet: A Spiking-Wavelet Fusion Network for Quality Enhancement of VVC-Compressed 360-Degree Video"**.
>
> **The full source code will be made publicly available immediately upon the acceptance of the paper.**

## 📖 Introduction

**SWFNet** is a novel neuromorphic-inspired architecture designed for the quality enhancement of VVC-compressed 4K and 8K panoramic videos. Functionally inspired by the **Magnocellular-Parvocellular (M-P)** dual-stream mechanism of the primate visual system, SWFNet explicitly decouples restoration into:

* **Global Stream (M-pathway):** Utilizes a **Transformer-SNN (TransSNN)** backbone to capture long-range structural dependencies and correct ERP geometric distortions via energy-efficient sparse spiking.
* **Local Stream (P-pathway):** Employs **Residual Wavelet Fusion (RWF)** modules to resolve high-frequency spatial details and remove quantization artifacts.

### Key Highlights:
* **🧠 Bio-Inspired Framework:** Synergizes global structural modeling with local fine-grained texture recovery, effectively handling the conflict between geometric correction and detail restoration.
* **⚡ Extreme Efficiency:** Achieves state-of-the-art fidelity with only **1.48M parameters** and **2.32 GFLOPs**, reducing computational costs by **~96%** compared to NAFNet.
* **🚀 8K Scalability:** The only tested model capable of feasible inference on **8K (8192×4096)** inputs, avoiding the Out-Of-Memory (OOM) issues common in conventional ViT-based models.

## 🖼️ Model Architecture

The overall architecture of the proposed SWFNet framework is shown below:
![SWFNet Architecture](https://github.com/user-attachments/assets/0acfb710-8856-42bd-aa1e-8b08e6f4f5ce)
