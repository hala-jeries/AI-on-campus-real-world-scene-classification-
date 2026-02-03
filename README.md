# AI on Campus: Real-World Scene Classification

## Overview
This project focuses on real-world campus scene classification using Deep Learning.
It addresses the domain shift problem by training a modern architecture on a custom, locally collected campus-scale dataset rather than relying solely on generic large-scale datasets.

## Dataset
- Approximately 2,400 RGB images
- 5 scene classes: Building, Car, Lab, Person, Tree
- Images collected from real-world campus and street environments
- Dataset is not included in this repository due to size limitations

## Model
- Architecture: ConvNeXt Tiny (pretrained on ImageNet)
- Framework: PyTorch
- Class imbalance handled using WeightedRandomSampler
- Robustness enhanced through data augmentation and label smoothing

## Results
- Training Accuracy: 99.43%
- Validation Accuracy: 99.12%
- Model behavior analyzed using Grad-CAM and t-SNE visualizations

## Repository Contents
- `code.ipynb` : Training and evaluation notebook
- `paper.pdf` : Full technical project paper

## Notes
This repository is intended to showcase the practical implementation and experimental results of the project. Detailed methodology, analysis, and discussion are provided in the accompanying paper.
