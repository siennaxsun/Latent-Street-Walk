# Latent-Street-Walk
**Deep learning (VAE) implementation to generate street layouts to guide future urban planning**


This project explores how deep learning—specifically Variational Autoencoders (VAE)—can learn from historical street networks to generate new urban layouts. Using a dataset of 592 road network images from 65 European cities, the model aims to capture latent urban design patterns and inspire future planning of undeveloped areas.

---

## 🧠 Project Scope

- Uses a **Variational Autoencoder** to reconstruct and generate urban street network patterns.
- Trained on images representing four layout styles: **medieval**, **grid**, **radial**, and **post-WW2**.
- Implemented using **TensorFlow** in **Google Colab**.

---

## 📂 Files

This repository includes the VAE implementation (`vae_latent_street_walk.ipynb`) as part of the project team. The image preprocessing and data collection scripts are not included here.

---

## 🧪 Highlights

- **Reconstruction Loss** and **KL Divergence** are minimized to balance fidelity and diversity in the latent space.
- K-Means clustering optionally used for post-analysis of latent vector groupings.
- Trained over 100 epochs with a learning rate of 0.0007.

---

## 🧰 Requirements

- Python 3.x  
- TensorFlow  
- NumPy  
- Matplotlib  
- Google Colab (recommended for training/testing)

---

## 🔖 Keywords

Urban Design • Generative Models • Variational Autoencoder • Deep Learning • Street Network Analysis
