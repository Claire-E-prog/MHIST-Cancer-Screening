# MHIST-Cancer-Screening
This was the computer vision capstone project for my ML Engineering bootcamp. The data and associated research used in this project can be found here: 'A Petri Dish for Histopathology Image Analysis' https://arxiv.org/abs/2101.12355

This project began as an exploration in building image recognition models from scratch and comparing the performance with pre-trained ResNet models in PyTorch.  

The project explores:

**Transfer Learning**: Utilized pre-trained ResNet models (e.g., ResNet18) with ImageNet weights, replacing the final fully connected layer to adapt the model to a specific classification task.
- **Freezing vs. Fine-Tuning**: Demonstrated two approaches:
  - **Freezing Pre-Trained Layers**: Kept the pre-trained layers fixed and trained only the final layer.
  - **Fine-Tuning**: Allowed all layers of the model to be fine-tuned on the target dataset.
- **Model Optimization**: Implemented **dropout** and **batch normalization** for regularization and enhanced model generalization.
- **Training Strategy**: Applied data augmentation, smaller learning rates, and various regularization techniques to prevent overfitting and improve performance on unseen data.
