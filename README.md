# Assignment-8
Advanced Convolutions &amp; Data Augmentation

# Dataset 
CIFAR10

# Library used
1. albumentations
2. numpy
3. torch

# Process Steps
  1. Data Preparation with Albumentations
    Albumentations Transformations to be applied to about 50% of images
      1. Horizontal flip
      2. Shift - shift 12.5 pixel (6.25%) translation in both Horizonta & Vertical
      3. Scale - Image scaled to 110% of its orginal size
      4. Rotate - 15 deg rotation
    
  2. Model Architecture - limiting the parameters to < 200K
  3. Training and Visualization - Took almost 130 Epochs to reach accuracy of > 85%
