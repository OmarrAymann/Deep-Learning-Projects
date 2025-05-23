# 🍠 Potato Disease Leaf Dataset (PLD)

This repository hosts the **Potato Disease Leaf Dataset (PLD)**, a curated collection of annotated images of potato leaves categorized by disease type. It is useful for building machine learning and deep learning models for plant disease detection and precision agriculture applications.
![po](https://github.com/user-attachments/assets/48e6915b-0857-4fba-98ba-a49ccc9161cb)

## 📂 Dataset Overview

- **Total Images**: 2,152  
- **Classes**: 3   
- **Source**: [Kaggle Dataset](https://www.kaggle.com/datasets/rizwan123456789/potato-disease-leaf-datasetpld/data)  

### Classes Included

| Class Name     | Description                                                   |
|----------------|---------------------------------------------------------------|
| `Early_Blight` | Caused by *Alternaria solani*, characterized by concentric spots. |
| `Late_Blight`  | Caused by *Phytophthora infestans*, appears as dark lesions.     |
| `Healthy`      | Leaves showing no visible signs of disease.                     |

## 🧪 Models & Experiments

The following models were trained and evaluated on this dataset:

| Model         | Description                         | Accuracy | Notes |
|---------------|-------------------------------------|----------|-------|
| CNN from Scratch | Custom-built convolutional network | 95%    | Lightweight, trained from ground up |
| ResNet50      | Pretrained on ImageNet, fine-tuned   | 96%    | Good baseline for transfer learning |
| MobileNet     | Pretrained lightweight model         | 97%    | Fast and efficient for deployment |

