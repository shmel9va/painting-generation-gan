# painting-generation-gan

This repo contains implementations of **DCGAN** and **CycleGAN** applied to Monet-style image generation and Photo↔Monet translation. It includes training scripts, inference utilities, visualization, and **FID/MiFID** evaluation.

- **Models:** DCGAN (generation from noise), CycleGAN (unpaired image-to-image, Photo↔Monet)
- **Data:** Kaggle Competition "I’m Something of a Painter Myself" Getting Started (Monet JPEG / Photo JPEG, 256×256)
- **Metrics:** FID and MiFID
- **Result snapshot:** MiFID — DCGAN ≈ 176.7, CycleGAN ≈ 66.9 (lower is better)
