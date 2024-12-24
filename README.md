---
title: Colorization
emoji: 📉
colorFrom: red
colorTo: purple
sdk: gradio
sdk_version: 5.7.0
app_file: app.py
pinned: false
license: apache-2.0
short_description: Deep Learning Project
---

**Check out the configuration reference at https://huggingface.co/docs/hub/spaces-config-reference**
***Colorizing Black-and-White Photos***
This project explores the intersection of technology and art by implementing and comparing image colorization models. The aim is to transform grayscale images into visually realistic and vibrant color images, addressing challenges in semantic understanding and aesthetic quality.

****Overview****
We implemented three main approaches:

1.Training from Scratch:
- UNet-based architecture.
- GAN-based architectures with ResNet and MobileNet backbones.
2. Pretrained Model:
- ControlNet-Stable Diffusion XL (SDXL) for advanced colorization.

****Methodology****
1. UNet: Encoder-decoder structure with skip connections for preserving spatial details.
2. GANs:
- ResNet-18 and MobileNetV2 backbones integrated into a U-Net framework.
- PatchGAN discriminator for enhancing texture and color consistency.
3. ControlNet-SDXL:
- Utilized diffusion models conditioned on grayscale images for stable colorization.

****Dataset****
1. PASCAL VOC 2012: Used for training UNet and GAN models.
2. COCO 2017: Utilized in pretrained ControlNet-SDXL.

****Demo****
Try the demo on Hugging Face Spaces: [Demo Link](https://huggingface.co/spaces/ChiKyi/Colorization)

****Full Reposity****
- https://github.com/TN8203/Colorizing-black-and-white-photo.git 
