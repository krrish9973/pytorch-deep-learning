# 🔥 pytorch-deep-learning

A curated collection of PyTorch deep learning projects demonstrating computer vision workflows—from classic image classification to modern optimization techniques and deployment.

---

## 📂 Projects Overview

### 1. **FashionMNIST Classifier (Milestone Project 1)**
- 📦 Classifies 10 types of clothing (t-shirts, coats, sneakers, etc.).
- Covers full workflow: data loading, CNN model training, performance analysis (accuracy, confusion matrix), and future enhancements.

### 2. **FoodVision Mini (Milestone Project 2)**
- 🍕🥩🍣 Multi-class classifier identifying pizza, steak, and sushi.
- Steps:
  1. Train baseline CNN from scratch on 10% & 20% of Food101 data subsets.
  2. Transfer learning experiments with EfficientNetB0 & Vision Transformer (ViT).
  3. Model comparison, evaluation, and deployed via [Gradio on Hugging Face Spaces](link).
- Demonstrates data scaling, model selection, and deployment knowledge.

### 3. **ResNet50 Optimization with `torch.compile()` (Milestone Project 3)**
- 🚀 Benchmarks ResNet50 on CIFAR-10 comparing standard vs PyTorch 2.x’s `torch.compile()`.
- Highlights runtime improvements and maintained accuracy—showing up-to-date performance optimization.

---

## 🛠️ Setup & Installation

1. **Clone the repo**
   ```bash
   git clone https://github.com/krrish9973/pytorch-deep-learning.git
   cd pytorch-deep-learning
