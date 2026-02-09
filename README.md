# BigGAN Image Generation

A PyTorch implementation of **BigGAN**, a state-of-the-art Generative Adversarial Network designed for **high-resolution image synthesis**.

This repository demonstrates model setup, training routines, sampling, and visualization of generated images across classes and latent space.

---

## 🚀 Project Overview

BigGAN (Big Generative Adversarial Networks) are powerful architectures capable of producing highly realistic images at multiple scales.

This project includes:
✔ BigGAN model implementation  
✔ Dataset handling  
✔ Training and evaluation scripts  
✔ Inference and sample generation  
✔ Visualization utilities  

---

## 🧠 What This Does

BigGAN learns to generate high-quality images by:
- Mapping random latent vectors + class labels  
- Producing images via a deep GAN architecture  
- Leveraging class conditioning for controlled generation  

Use cases:
- Image synthesis / creative generation
- Latent space exploration
- GAN research benchmarking
- Dataset augmentation

---

## 🛠️ Tech Stack

- Python 3.8+
- PyTorch
- NumPy
- torchvision
- Matplotlib / PIL

---

## 📦 Installation

Clone the repository:

```bash
git clone https://github.com/Hari7383/biggan-image-generation.git
cd biggan-image-generation
```
Create a virtual environment:
```
python -m venv venv
source venv/bin/activate     # Linux / Mac
venv\Scripts\activate        # Windows
```
