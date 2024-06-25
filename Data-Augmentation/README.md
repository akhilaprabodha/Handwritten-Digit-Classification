# 🧠 Digit Classification with Denoising Autoencoder 🖼️

Welcome to the Digit Classification project! This project leverages the power of neural networks to classify handwritten digits (0-9) while using an autoencoder to remove noise from digit images, ensuring cleaner and more accurate classification results. 🚀

<div align="center">
  <img src="https://github.com/akhilaprabodha/Handwritten-Digit-Classification/assets/123384639/628ed344-2e08-4d35-a4ba-97b87786b3de" alt="drawing" width="80%">
</div>

## 📁 Project Overview

This repository contains the code and resources for building and training an autoencoder to denoise digit images, followed by a classifier to identify the digits. The main components are:

1. **Autoencoder**: A neural network trained to remove noise from images. 🌟
2. **Classifier**: A neural network trained to classify the denoised digit images. 🔢

<div align="center">
<img src="https://github.com/akhilaprabodha/Handwritten-Digit-Classification/assets/123384639/864d1bda-0ac3-462d-a8f2-5f48f1fadef0" alt="drawing" width="500"/>
</div>

## 📜 Features

- **Noise Removal**: The autoencoder efficiently removes noise from input images, enhancing the clarity and quality of digit representations. 🧼
- **Digit Classification**: Accurate classification of digits (0-9) using a convolutional neural network (CNN). 🔍
- **Dataset**: Uses the MNIST dataset for training and evaluation. 🗂️

## 🛠️ Installation

To get started, clone the repository and install the required dependencies:

```bash
git clone https://github.com/yourusername/digit-classification-denoising-autoencoder.git
cd digit-classification-denoising-autoencoder
pip install -r requirements.txt
```

## 🚀 Usage

Follow these steps to train the autoencoder and classifier:

1. **Prepare the Data**: Load the MNIST dataset and add noise to the digit images.
2. **Train the Autoencoder**: Train the autoencoder to learn how to remove noise from the images.
3. **Train the Classifier**: Use the denoised images to train the classifier.
4. **Evaluate**: Evaluate the performance of the classifier on the test set.

Run the Jupyter notebook `Build an Autoencoder.ipynb` to see the full process in action. 📓

## 📊 Results

The autoencoder successfully reduces noise in the digit images, leading to improved classification accuracy. Below are some examples of noisy images, denoised images, and their corresponding classifications.

| **Noisy Image** | **Denoised Image** | **Classification** |
|:-------------:|:----------------:|:----------------:|
| ![noised 7](https://github.com/akhilaprabodha/Handwritten-Digit-Classification/assets/123384639/dfe8fec2-9e21-4ea2-b405-299cf7dd2a97)| ![denoised 7](https://github.com/akhilaprabodha/Handwritten-Digit-Classification/assets/123384639/07d32152-a004-40b8-b9c8-e15c96106acc) | 7 |

## 🤝 Contributing

Contributions are welcome! If you have any improvements or suggestions, please create a pull request or open an issue. Let's make this project better together! 💡

## 📄 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.







