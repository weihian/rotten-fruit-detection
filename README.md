# Rotten Fruit Detection using Deep Learning

This repository features an automated system designed to classify fruit quality as either **Fresh** or **Rotten**. By utilizing Deep Learning and Computer Vision, this project provides a scalable solution for food waste reduction and automated quality assurance in the agricultural sector.


## 🍎 Project Overview

The objective of this project is to develop a robust classifier capable of identifying spoilage in common fruits (Apples, Oranges, Bananas, etc.). The model processes image data to detect physical signs of decay, bruising, or mold that characterize rotten fruit.

### Key Results:
- **Final Accuracy:** 98.55% on the validation set.
- **Classification Performance:** Successfully surpassed the target threshold of 93% accuracy.

## 🛠️ Technical Stack

- **Framework:** PyTorch
- **Language:** Python
- **Infrastructure:** Google Colab with T4 GPU acceleration
- **Core Libraries:** Torchvision, NumPy, Matplotlib, PIL

## 🔬 Model Architecture

The system utilizes a Convolutional Neural Network (CNN) architecture optimized for feature extraction from high-resolution imagery.


### The Pipeline:
1.  **Preprocessing:** Images are resized and normalized to ensure consistent input for the neural network.
2.  **Feature Extraction:** Multiple convolutional layers identify textures and color patterns associated with rot.
3.  **Classification:** A fully connected layer outputs the probability of the fruit being fresh or rotten.
4.  **Validation:** The `utils.validate` function monitors performance using Loss and Accuracy metrics to prevent overfitting.

## 📂 Project Structure

```text
├── Individual_Assignment_2.ipynb  # Comprehensive training and evaluation notebook
├── dataset/                       # Classified images (Fresh/Rotten)
└── README.md                      # Project documentation
