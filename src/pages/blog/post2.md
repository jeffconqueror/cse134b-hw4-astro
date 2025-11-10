---
layout: ../../layouts/BaseLayout.astro
title: "Low-Light Image Enhancement with Deep Learning"
pubDate: 2025-01-10
description: "Deep learning approach for enhancing images captured in poor lighting conditions"
---

# Low-Light Image Enhancement with Deep Learning

## Overview

This project focuses on developing a deep learning model that enhances images taken in low-light conditions while preserving important details and avoiding over-exposure artifacts.

## The Problem

Images captured in low-light environments suffer from:
- Low visibility and poor contrast
- High noise levels
- Loss of color information
- Difficulty in identifying important details

## Our Approach

We developed a CNN-based architecture that:
1. **Analyzes** the illumination map of the input image
2. **Separates** noise from actual image content
3. **Enhances** brightness while preserving natural colors
4. **Restores** fine details lost in dark regions

## Key Technologies

- **PyTorch**: Deep learning framework
- **CNN Architecture**: Custom encoder-decoder network
- **LOL Dataset**: Low-light image pairs for training
- **OpenCV**: Image processing and evaluation

## Results

Our model achieved:
- **PSNR**: 24.5 dB on test set
- **Processing Time**: 50ms per image on GPU
- **Visual Quality**: Natural-looking enhancements without artifacts

Published at IJCNN 2025 as "RSEND: Retinex-based Squeeze-and-Excitation Network with Dark channel prior"

## Before/After Examples

The model successfully enhanced cathedral interiors, street scenes, and indoor photography while maintaining natural color balance and avoiding the "washed out" appearance common in traditional enhancement methods.

## Future Work

- Real-time video enhancement
- Mobile device optimization
- Adaptive enhancement based on scene content

[View Paper](#) | [GitHub Repository](#)