# Computer Vision — Practical Guide

## Overview
This module covers modern computer vision techniques with practical examples and code snippets. Focus areas include image classification, CNNs, object detection, segmentation, transfer learning, and deployment.

## Learning Objectives
- Understand convolutional neural networks (CNNs) and their building blocks
- Implement image classification pipelines using PyTorch/TensorFlow
- Use transfer learning with pre-trained models (ResNet, EfficientNet)
- Implement object detection with YOLO/Detectron2/SSD concepts
- Perform semantic segmentation and instance segmentation
- Deploy CV models (TorchServe, TensorFlow Serving, ONNX)

## Notebooks / Sections
1. Intro to CNNs — theory and small CNN from scratch
2. Image Classification — dataset pipelines, augmentation, training loops
3. Transfer Learning — finetuning pre-trained models
4. Object Detection — dataset formats (COCO), architectures, inference
5. Segmentation — U-Net, DeepLab
6. Deployment — export models, optimize with ONNX/Tensorrt

## Example: Simple PyTorch Training Loop
```python
import torch
import torch.nn as nn
import torch.optim as optim
from torchvision import datasets, transforms, models

transform = transforms.Compose([
    transforms.Resize(224),
    transforms.CenterCrop(224),
    transforms.ToTensor(),
])

dataset = datasets.FakeData(transform=transform)
loader = torch.utils.data.DataLoader(dataset, batch_size=16)

model = models.resnet18(pretrained=False)
model.fc = nn.Linear(model.fc.in_features, 10)

criterion = nn.CrossEntropyLoss()
optimizer = optim.SGD(model.parameters(), lr=0.01)

for epoch in range(2):
    model.train()
    for x, y in loader:
        optimizer.zero_grad()
        preds = model(x)
        loss = criterion(preds, y)
        loss.backward()
        optimizer.step()
    print(f"Epoch {epoch} done")
```

## Exercises
- Build an image classifier on CIFAR-10 using transfer learning
- Implement Grad-CAM for model interpretability
- Train a U-Net on a simple segmentation dataset

---

> See also: deployment and dataset preparation tips in the `resources` folder.