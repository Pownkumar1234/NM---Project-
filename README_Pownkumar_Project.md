# Handwritten Digit Recognition using Deep Learning

Welcome to my deep learning project! This repository contains a complete implementation of a **Handwritten Digit Recognition System** using a **Convolutional Neural Network (CNN)** and an interactive drawing interface. It runs fully on **Google Colab** using the `ipycanvas` library for real-time digit input.

## Project Information

- **Project Title**: Handwritten Digit Recognition using Deep Learning
- **Author**: Pownkumar
- **Date**: 10th May 2025
- **Platform**: Google Colab
- **Dataset**: [MNIST Handwritten Digits Dataset](http://yann.lecun.com/exdb/mnist/)

## Features

- Draw your digit in a Colab notebook using your mouse or touchpad.
- Predict the digit using a trained CNN model.
- Shows prediction with confidence score.
- Fully browser-based — no need for local installations.

## Getting Started

### 1. Open in Google Colab

- Upload the notebook: `Digit_Recognition_Colab_Compatible.ipynb`
- Or launch from GitHub if linked directly to Colab.

### 2. Run All Cells

- Install dependencies (`ipycanvas`, `tensorflow`)
- Train or load the CNN model
- Use the drawing canvas to test digit recognition

## Model Architecture

- **Input Layer**: 28x28 grayscale image
- **Layers**:
  - Conv2D (32 filters) + MaxPooling
  - Conv2D (64 filters) + MaxPooling
  - Flatten → Dense (100) → Dense (10, Softmax)
- **Output**: Probability distribution for digits 0–9

## Example

![Sample Demo](demo_screenshot.png)

## Libraries Used

- Python
- TensorFlow / Keras
- ipycanvas (for interactive canvas)
- OpenCV (for preprocessing)

## Controls

| Action       | Description                    |
|--------------|--------------------------------|
| **Draw**     | Use mouse or trackpad          |
| **Predict**  | Click Predict button           |
| **Clear**    | Click Clear to reset canvas    |

## Folder Structure

```
├── Digit_Recognition_Colab_Compatible.ipynb
├── README.md
├── demo_screenshot.png
```

## License

This project is licensed under the [MIT License](LICENSE). You are free to use, modify, and distribute it with credit.

---

**Made with passion for AI and Deep Learning by Pownkumar**  
**Date**: 10th May 2025