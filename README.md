# 🏅 Sports Image Classification

This is a small demo project I made to showcase how I approach an image classification task with PyTorch.  
It’s not meant to be a production-ready solution, but more of an example of how I structure code, work with datasets, train models, and track experiments.

---

## What’s inside?

- A **custom dataset class** for loading and preprocessing sports images  
- **Transforms & augmentations** with `torchvision.transforms.v2`  
- Handling **class imbalance** and using **balanced accuracy** as an additional metric  
- Fixed seeds for reproducibility  
- **Learning rate scheduler** for smoother training  
- Integration with **Weights & Biases (W&B)** for experiment tracking  
- Training a **ResNet-50** model

---

## Libraries I used

- Python basics: `os`, `glob`, `random`, `typing`
- Image processing: `cv2`, `PIL`
- Data science: `numpy`, `pandas`, `seaborn`, `matplotlib`
- Deep learning: `torch`, `torchvision`
- Metrics: `sklearn.metrics` for balanced accuracy & confusion matrix
- Experiment tracking: `wandb`
- Progress bar: `tqdm`

---

## Results

| Phase        | Accuracy | Balanced Accuracy | Loss    |
|--------------|----------|-------------------|---------|
| Train        | 97.9%    | 97.9%             | 0.08707 |
| Validation   | 98.8%    | 98.8%             | 0.04872 |
| Test         | 99%      | 99%               | 0.03614 |

---

## Why I made this

This project is just a **small demonstration of my coding style** and how I think about:
- Organizing a training pipeline  
- Working with custom datasets  
- Dealing with class imbalance  
- Tracking experiments and metrics properly  

It’s not a big research project, but if you want to see how I code and structure an image classification task, this repo is a simple example.

---

## Note

This is just for demonstration purposes. If you want to run it yourself, you can check the code and configs, but keep in mind it’s built as a showcase rather than a full production setup.
