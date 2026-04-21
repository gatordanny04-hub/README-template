# Project 3 - Artificial Neural Networks (Lung X-Ray Classification)

## About The Project

This project focuses on multi-label classification of lung diseases using a Convolutional Neural Network (CNN) applied to chest X-ray images. The dataset used is ChestMNIST, which contains grayscale X-ray images labeled across 14 disease categories.

The goal of this project is to build a deep learning model capable of predicting multiple diseases simultaneously from a single image. The model was trained using TensorFlow/Keras and evaluated using Binary Accuracy and AUC metrics.

The final model achieved:
- Test Accuracy: 94.77%
- Test AUC: 0.8296

For detailed methodology and analysis, please refer to the project report.

---

## Built With

- Python 3
- TensorFlow / Keras
- NumPy
- Matplotlib

---

## Getting Started

To run this project locally, follow the steps below.

---

## Dependencies

The following libraries are required:

- Python 3.8+
- TensorFlow 2.x
- NumPy
- Matplotlib

You can install them using:

```bash
pip install tensorflow numpy matplotlib

## INstallation

git clone https://github.com/YOUR_USERNAME/project-3-undergrad-gatordanny04-hub.git
cd project-3-undergrad-gatordanny04-hub
Usage
Step 1: Dataset

Download the dataset from Canvas and place it in the root directory: chestmnist.npz
Step 2: Train the Model

Run the training notebook:Training.ipynb
This will:

preprocess the dataset
train the CNN model
save the trained model

Output files:model_dataset1.keras
best_model_dataset1.keras

Step 3: Test the Model

Run the test notebook:Test.ipynb

This will:

load the trained model
evaluate performance on the test set
generate predictions

Results

The model demonstrates strong performance across datasets.
| Metric              | Value  |
| ------------------- | ------ |
| Training Accuracy   | 0.9492 |
| Validation Accuracy | 0.9493 |
| Test Accuracy       | 0.9477 |
| Training AUC        | 0.8488 |
| Validation AUC      | 0.8286 |
| Test AUC            | 0.8296 |

Roadmap
Improve model performance with deeper architectures
Apply transfer learning
Use higher-resolution images
Address class imbalance
Authors

Daniel Hwang
University of Florida

Acknowledgements
University of Florida (Canvas Course Materials)
ChestX-ray14 Dataset (NIH)
MedMNIST Benchmark
TensorFlow Documentation

REFERENCES
D. Hwang, “Project 3 – Multi-Label Classification of Lung Diseases Using Convolutional Neural Networks on Chest X-Ray Images” GitHub repository, 2026. [Online]. Available: https://github.com/UF-AML-Spring-2026/project-3-undergrad-gatordanny04-hub.git.
University of Florida, “ChestMNIST Dataset,” Canvas Course Files, 2026. Available: https://ufl.instructure.com/courses/555954/files/folder/Projects/Project%203?preview=103166351

