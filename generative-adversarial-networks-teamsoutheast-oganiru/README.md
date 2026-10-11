[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/5Hlx6Kc7)
# Week 9 GAN Assignment

Complete the following tasks in your project:

---

## Q1: Apply RescaleIntensity Transform
- Insert TorchIO’s `RescaleIntensity` transform  
- Clip voxel intensities between the 0th and 99.5th percentiles  
- Reference: https://torchio.readthedocs.io/transforms/preprocessing.html

---

## Q2: Replace Generator with U‑Net
- Swap out the existing Generator network for a U‑Net architecture of your choice  
- **Extra credit:** use a SwinUNETR instead of a vanilla U‑Net

---

## Q3: Configure W&B Experiment Tracking
- Sign up at https://wandb.ai/ and generate your API key  
- Paste your API key into the “WANDB Logging” cell to enable run tracking  
