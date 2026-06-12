# Waste Segregation Using Hybrid Deep Learning Model

This project presents an intelligent waste classification system using a Hybrid Deep Learning Architecture that combines ResNet18 and Vision Transformer (ViT) models. The system automates recyclable waste segregation by leveraging both local spatial features and global contextual relationships from waste images.

## Dataset
The model is trained on the WaRP-C (Waste Recycling Plant Classification) Dataset containing 10,406 images across five recyclable waste categories:

- Plastic Bottles
- Glass Bottles
- Cardboard Cartons
- Detergent Containers
- Metal Cans / Canisters

The dataset includes real-world challenges such as lighting variations, background clutter, object orientation changes, and visually similar waste classes.

## Methodology

1. Data Preprocessing and Augmentation
2. Feature Extraction using Pretrained ResNet18
3. Patch Encoding of CNN Features
4. Global Feature Learning using Vision Transformer
5. Feature Fusion and Classification
6. Model Training and Evaluation

## Technologies Used

- Python
- PyTorch
- Torchvision
- NumPy
- Pandas
- Scikit-Learn
- Google Colab
- NVIDIA T4 GPU
- Vision Transformer (ViT)
- ResNet18

## Results

- Accuracy: 92.39%
- Precision: 92.25%
- Recall: 92.39%
- F1-Score: 86.66%

## Applications

- Smart Waste Management Systems
- Automated Recycling Plants
- Smart City Infrastructure
- Sustainable Environmental Monitoring

## Future Scope

- Lightweight Transformer Architectures
- Real-Time Smart Bin Deployment
- Edge Device Integration
- Semi-Supervised Learning for Waste Classification
