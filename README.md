# 🔐 Chaos-Based Image Encryption

An implementation of **image encryption using chaotic mathematical maps** that demonstrates how chaos theory can be applied to cryptography for secure image scrambling.

## 🌀 Overview

This project explores **chaos-based cryptography** by implementing three different chaotic maps to encrypt images. The system leverages the sensitive dependence on initial conditions inherent in chaotic systems to create secure, visually scrambled images that can be perfectly decrypted with the correct parameters.

## 📊 Implemented Chaos Maps

- **Arnold Cat Map**: 2D area-preserving geometric transformation with excellent mixing properties
- **Henon Map**: Classic discrete-time dynamical system using sequence-based XOR encryption
- **Logistic Map**: Simple yet chaotic 1D map for pixel value transformation

## 🔬 Security Analysis Features

- **Histogram Analysis**: Measures encryption uniformity
- **Adjacent Pixel Correlation**: Tests pixel pattern breaking
- **Information Entropy**: Calculates randomness in encrypted images
- **Key Sensitivity**: Verifies small key changes produce different results

## 📈 Key Results

- Strong key sensitivity (>50% pixel changes with minor key modifications)
- Improved entropy and reduced correlation in encrypted images
- Perfect decryption capability with correct parameters
- Visual demonstration of chaos theory in cryptographic applications

## 🚀 **[📓 View Interactive Colab Notebook](https://colab.research.google.com/drive/1xAFMDmaa8EGEBUt6IfLk7i_HamctlZWQ?usp=sharing)**

*Complete implementation with experiments and security analysis*

## 🛠️ Technologies Used

**Python** • **NumPy** • **Matplotlib** • **PIL** • **SciPy** • **Google Colab**

---

*Built for research in chaos theory, cryptography, and image security applications.*
