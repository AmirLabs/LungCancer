# Chest X-Ray Classification

This project classifies chest X-ray images as "normal" or "pneumonia" using a Convolutional Neural Network (CNN).

## Dependencies

- Python 3.x, TensorFlow, Keras, Numpy, Pandas, Scikit-learn

## Dataset

The dataset consists of chest X-ray images stored in `data/` (training) and `test_data/` (testing) directories.

## Model Architecture

CNN with 3 Conv2D layers, MaxPooling, and Dense layers for binary classification.

## How to Run

1. Organize your dataset in `data/` and `test_data/`.
2. Run the script:

```bash
python train_model.py