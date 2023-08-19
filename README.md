In this deep learning project, I plan to train a semantic segmentation model on a Brain Tumor 2D MRI Slices database, provided by Balakrishna Kumar.

I'll use MONAI and PyTorch libraries for data wrangling and creating models.

T4 GPU of google colab will be used for this session.

Table of Contents:

*   Intro 1: Installing Libraries
*   Intro 2: Importing Necessary Modules
*   Intro 3: Deterministic Programming
*   Part 1: Data Collection
*   Part 2: Data Wrangling / Analysis / Preprocessing Steps
   - Part 2.1: First Glance
   - Part 2.2: Creating Primary Frame
   - Part 2.3: Exploratory Data Analysis (EDA)
   - Part 2.4: Mask Modifications
   - Part 2.5: Splitting data and Finalizing the Frame
   - Part 2.6: Creating Train/Val/Test lists
   - Part 2.7: Building Data Loaders

*   Part 3: Loading the Model's Architecture
*   Part 4: Training the Model for Locating ROI
    - Part 4.1: Defining A Metric Function
    - Part 4.2: Defining A Loss Function
    - Part 4.3: Evaluating the Untrained Model's Performance to Determine Our Baseline
    - Part 4.4: Building A Trainer
    - Part 4.5: Training a Model (UFlex)
    - Part 4.6: Training a Model (CustomUNet)

*   Part 5: Evaluating the Trained Models
    - Part 5.1: Evaluating Trained Uflex
    - Part 5.2: Evaluating Trained CustomUNet


Dataset Information:
    - Title of Dataset: Brain 2D MRI Images and Mask
    - Provided by: Balakrishna Kumar
    - Description: 4715 (.h5) files containing:
        1.   The actual 2D Brain Images (FLAIR channel)
        2.   Corresponding masks for tumor segmentation  
    - Extracted from: 3D BraTS-2019
Link:
    https://www.kaggle.com/datasets/balakrishcodes/brain-2d-mri-imgs-and-mask
