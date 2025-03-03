# InceptionNet-AppleLeaf-Disease-Detection

This repository contains an **InceptionV3** deep learning model for detecting apple leaf diseases. The model classifies leaves into **Healthy, Rust, Scab, or Multiple Diseases** using multi-scale feature extraction.

![image](https://github.com/user-attachments/assets/fc648d8a-9d7e-426c-8205-b70d4d737345)![image](https://github.com/user-attachments/assets/5c8525cb-057d-4a16-af33-b9becdda3045)![image](https://github.com/user-attachments/assets/7373b489-1ca5-434c-b42b-bafe6d691db1)![image](https://github.com/user-attachments/assets/2fa3d99d-28da-4e52-b16c-b0571ecd1bdb)


## Dataset
- Dataset: [Plant Pathology 2020 - FGVC7 | Kaggle](https://www.kaggle.com/competitions/plant-pathology-2020-fgvc7)
- Includes labeled apple leaf images.

## Model Overview
- **Inception modules** capture features at multiple scales.
- Uses **pre-trained ImageNet weights** for transfer learning.
- **Global Average Pooling (GAP)** to reduce overfitting.
- Final classification through a **Softmax layer**.

## Installation & Requirements
To run this project, install dependencies:
```bash
pip install tensorflow keras numpy pandas matplotlib seaborn
```

## Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/InceptionV3-AppleLeaf-Disease-Detection.git
   cd InceptionV3-AppleLeaf-Disease-Detection
   ```
2. Open and run `inceptionv3_model.ipynb` in Jupyter Notebook or Google Colab.
3. Load the dataset and train the model.

## Results
- Achieved **93% accuracy** on test data.
- Performs well but slightly behind **DenseNet121**.

## Future Improvements
- Fine-tuning on a larger dataset.
- Implementing **attention mechanisms** for better disease localization.

## License
This project is licensed under the **MIT License**.
