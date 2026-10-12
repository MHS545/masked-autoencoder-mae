# Masked Autoencoder (MAE) — Self-Supervised Image Representation Learning

Implementation of **Masked Autoencoders** for self-supervised visual representation learning (He et al., 2021), built as Assignment 2 for the Generative AI course (AI4009).

## 🧠 What's inside

The notebook (`genai-assignment-no-2.ipynb`) walks through a complete MAE pipeline:

1. **Dataset** — Tiny ImageNet loader with preprocessing
2. **Patchification & masking** — image → patches, random masking of patch tokens
3. **Transformer building blocks** — encoder/decoder implemented from scratch
4. **Training** — reconstruct masked patches; learn representations without labels

## 🛠️ Tech

Python · PyTorch · Vision Transformers · Jupyter

## 🚀 Run it

```bash
pip install torch torchvision matplotlib
jupyter notebook genai-assignment-no-2.ipynb
```
