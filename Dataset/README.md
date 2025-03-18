# Dataset Overview

This directory contains the dataset used for the landslide prediction project. The data is split into three sets: training, validation, and test. Each set contains multispectral image patches in H5 format and is organized into subfolders.

[Dataset](https://drive.google.com/drive/folders/1Xz4ZYCyQBUJIwn5PLON42LclyB-xG0I1?usp=drive_link)

## Dataset Structure

The dataset is organized as follows:

### Training Data

- **`/train/images/`**: Contains the image patches used for training. Each image is a composite of 14 bands from Sentinel-2, ALOS PALSAR slope data, and Digital Elevation Model (DEM) data.
- **`/train/masks/`**: Contains the corresponding masks for each image in the training set. These masks are used for supervised learning, where the model learns to predict landslide occurrence or risk.

### Validation Data

- **`/validation/images/`**: Contains the image patches used for validation. These images are used to evaluate the model’s performance during training.
- **`/validation/masks/`**: Contains the corresponding validation masks.

### Test Data

- **`/test/images/`**: Contains the image patches used for testing. These images are used to assess the final performance of the trained model.
- **`/test/masks/`**: Contains the corresponding test masks.


