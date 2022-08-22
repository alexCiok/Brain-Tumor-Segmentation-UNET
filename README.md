# Brain-Tumor-Segmentation-UNET
Implementation of a CNN centered U-Net architecture for image segmentation of brain tumors on MRI Images using TensorFlow.

# Data
The images used for training were MR images (FLAIR) of patients with glioblastomas (brain tumor).
Database used : The Cancer Imaging Archive (https://www.kaggle.com/datasets/mateuszbuda/lgg-mri-segmentation)

# Pre-Processing
A 72/28 train/test split was used, and data augmentation was performed prior to training.
Performance was measured using Binary Cross-Entropy + Dice Coefficient Factor

# Training
The model was trained for 5 epochs using early stopping and best weights were saved.

# Results
The model performed well. Glioblastomas are easily detectable and often quite obvious.

**Accuracy :** 98.93%

**DCF :** 1.14%

![image](https://user-images.githubusercontent.com/52026069/185948590-39e5bc50-78d4-409f-8fd4-346ccdfac60b.png)
