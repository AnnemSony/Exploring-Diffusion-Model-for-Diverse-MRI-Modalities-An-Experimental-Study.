# Exploring Diffusion Models for Diverse MRI Modalities

This repository presents an experimental study on how diffusion models perform across various types of MRI images — specifically **brain**, **chromatin**, **lung**, **spine**, and **heart** scans. Each modality is explored independently to understand the model’s strengths, limitations, and reconstruction quality for the unique structural characteristics found in different parts of the human body.

## 🧠 Project Overview

Diffusion models have emerged as powerful generative models for high-quality image synthesis. This project evaluates their capability in reconstructing and enhancing medical MRI images using separate diffusion models tailored to individual image modalities.

### Modalities Included:
- 🧠 Brain MRI
- 🧬 Chromatin Cell Structures
- 🫁 Lung MRI
- 🦴 Spine MRI
- ❤️ Heart MRI

## 📌 Key Highlights

- **Independent Model Training**: Each MRI type is trained with a dedicated diffusion model.
- **Quality Assessment**: Models are evaluated using metrics such as **PSNR**, **SSIM**, **MSE**, **MAE**, and **FID**.
- **Medical Relevance**: The results show potential for improving scan clarity in fast or low-quality MRI acquisitions.
- **Scalability**: Framework can be adapted to new MRI types or other medical imaging modalities.


