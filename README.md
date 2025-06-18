# 🖼️ Neural Style Transfer using PyTorch

This project demonstrates **Neural Style Transfer**, a deep learning technique that combines the **content of one image** with the **style of another** using a pretrained **VGG19** network in PyTorch.

## 📌 Project Overview

- **Objective**: Blend two images — one for content and another for style — to create a stylized image.
- **Architecture**: Uses pretrained **VGG19** to extract features at specific layers.
- **Optimization**: Generated image is optimized by minimizing **content loss** and **style loss**.

## 🧠 Key Concepts

- **Content Loss**: Difference between high-level feature maps of the generated and original image.
- **Style Loss**: Computed using **Gram matrices** to capture texture and style from the style image.
- **Total Loss**: `Total = α * Content Loss + β * Style Loss`

## 🔧 Technologies Used

- Python
- PyTorch
- torchvision
- PIL (Python Imaging Library)

## 🖼️ Input Images

- **Content Image**: `images/my_image.jpg`
- **Style Image**: `images/style.jpg`

## 🙌 Acknowledgements

- **Inspired by Leon A. Gatys et al., who pioneered Neural Style Transfer.
