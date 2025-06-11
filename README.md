# 🏋️‍♂️ Sports Image Classification

This repository contains a deep learning pipeline for classifying sports-related images using PyTorch. It includes training, validation, early stopping, and performance visualization with Weights & Biases (`wandb`).

## 📁 Dataset
The dataset consists of labeled sports images. Paths to images and their corresponding labels are stored in a DataFrame.


## 🧠 Model Training
### Key Features
- PyTorch-based CNN model
- Unified `run_epoch()` function for training/validation/testing
- Early stopping based on validation loss
- Scheduler support: cosine, step, etc.
- Logging with Weights & Biases (wandb)

### Training Loop
```python
for epoch in range(config.epochs):
    run_epoch(..., 'train', ...)
    run_epoch(..., 'validation', ...)
    # Early stopping logic

