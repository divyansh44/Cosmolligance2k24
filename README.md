# Cosmolligance2k24
# Flood Segmentation Using UNet with Batch Normalization

## Objective
The goal of this project is to accurately segment flood-affected areas in satellite imagery using a UNet model with **Batch Normalization** for improved training stability and generalization.

## Approach
- **Model**: UNet architecture with added Batch Normalization layers.
- **Loss Function**: Binary Cross-Entropy (BCE) loss for pixel-wise classification.
- **Metrics**: 
  - IoU (Intersection over Union)
  - Dice Coefficient
- **Data**: 290 images with data augmentation (flips, rotations, scaling, etc.) to improve model robustness.
- **Challenge**: Hand-labeled masks with inaccuracies.

## Results
- **Validation IoU**: 0.7851
- **Validation Dice**: 0.8729

## Resources
- [https://github.com/divyansh44/Cosmolligance2k24/blob/main/cosmo-base.ipynb](#)
- [https://github.com/divyansh44/Cosmolligance2k24/blob/main/Flood-Segmentation-Project-Robust-Model-Development-2.pdf](#)

---

**Team Purple**  
Members: Geeth, Green, Divyansh
