# Cats vs Dogs Classification using Transfer Learning (MobileNetV2)

This project demonstrates the power of **Transfer Learning** using the **MobileNetV2** architecture to classify images of cats and dogs. Transfer learning allows the use of a pre-trained model on a new task, significantly reducing the training time and improving performance, especially when working with limited data.

### Project Overview

The goal of this project is to build an image classification model that can differentiate between images of **cats** and **dogs** using the **MobileNetV2** pre-trained model, fine-tuned for this task.

### Key Features

- **Transfer Learning**: Utilized **MobileNetV2**, a lightweight and efficient model pre-trained on ImageNet, to classify cats and dogs.
- **Preprocessing**: Performed image resizing, normalization, and data augmentation to improve model generalization.
- **Fine-Tuning**: Fine-tuned the MobileNetV2 model to adapt it to the cats vs dogs classification task.

### Dataset

The dataset used for this classification consists of labeled images of cats and dogs. It is publicly available and can be downloaded from the following link:

- **Dataset Link**: [Kaggle Cats vs Dogs Dataset](https://www.kaggle.com/c/dogs-vs-cats/data)

The dataset is split into two parts:
- **Training Set**: Images used to train the model.
- **validation Set**: Images used to validate the model.
- **Test Set**: Images for internet.
  
 ### Technologies Used

- **TensorFlow** and **Keras**: For building and training the deep learning model.
- **MobileNetV2**: Pre-trained model used for transfer learning.
- **NumPy** and **Pandas**: For data handling and manipulation.
- **Matplotlib** and **Seaborn**: For visualizing the results and training process.
- **OpenCV**: For image preprocessing.

  

