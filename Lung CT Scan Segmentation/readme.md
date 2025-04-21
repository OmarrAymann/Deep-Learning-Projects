# Lung CT Scan Segmentation

This project focuses on building a **U-Net model** for **image segmentation** of lung fields from **chest CT scans**. The task is to segment the lung fields into two classes: **lung** and **background** (chest). The goal is to automate the segmentation process, which is critical in diagnosing respiratory conditions from CT images.

## Key Features

- **Automatic Infected Area Detection**: Segments infected regions in chest CT scans.
- **End-to-End Workflow**: Includes data preprocessing, model training, and evaluation.
- **Clear Documentation**: Provides well-documented Jupyter notebooks for easy replication and understanding.

## Dataset

This project uses a **chest CT scan dataset** where each image is accompanied by a corresponding mask indicating the infected regions. The dataset should be organized into two directories: `images/` for the CT scan images and `masks/` for the binary masks that label the infected areas.


## Technologies Used

- **TensorFlow** and **Keras**: For building, training, and evaluating the deep learning model.
- **OpenCV**: For image preprocessing and augmentation.
- **NumPy** and **Pandas**: For data manipulation and analysis.
- **Matplotlib** and **Seaborn**: For visualizing the results.

## Results and Insights
- **Accuracy**: Achieved an accuracy of 98.9% on the test dataset.
- **Segmentation Quality**: The model effectively detects and segments infected regions, especially in clearer CT scans.
- **Scalability**: The model can be adapted for other medical imaging tasks, such as brain or liver segmentation.

