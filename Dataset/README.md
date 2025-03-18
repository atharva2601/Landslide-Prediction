# Dataset Overview

This directory contains the dataset used for the landslide prediction project. The data is split into three sets: training, validation, and test. Each set contains multispectral image patches in H5 format and is organized into subfolders.

[Dataset](https://eod-grss-ieee.com/dataset-detail/MkJ2T3pJM0p3eGh1QkZwRVZFa0FsZz09)

In the dataset, we have used in this project consists of training, validation, and test sets containing 3799, 245, and 800 image patches, respectively. All the images in the data are in h5 format. Each image patch is a composite of 14 bands that include:
● Multispectral data from Sentinel-2: B1, B2, B3, B4, B5, B6, B7, B8, B9, B10, B11, B12.
● Slope data from ALOS PALSAR: B13.
● Digital elevation model (DEM) from ALOS PALSAR: B14.

<img width="518" alt="image" src="https://github.com/user-attachments/assets/f393e8c0-b7b3-4de1-afdb-01c78ed193a9" />


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


