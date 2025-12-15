# Hand Gesture Recognition – Model Comparison

##  Project Overview
This project presents a comparative study of four deep learning architectures for hand gesture classification using the same dataset but different preprocessing pipelines and model architectures.

##  Implemented Models
1. VGG-19 architecture implemented from scratch
2. ResNet (pre-trained) using transfer learning
3. Inception V1 (pre-trained) using transfer learning
4. MobileNetV2 (pre-trained) using transfer learning

##  Dataset
- The dataset used in this project is the **Kaggle Hand Gesture Recognition Dataset**.

🔗 Dataset Link:  
-  (https://www.kaggle.com/datasets/gti-upm/leapgestrecog)
The dataset is not included in this repository due to its large size.

##  All models are trained on the same dataset.
###   - Differences between models lie in preprocessing steps and model architectures only, ensuring a fair comparison.

##  Preprocessing
Each model applies preprocessing techniques suited to its architecture, including:
- Image resizing
- Normalization
- Grayscale to RGB conversion (when required)
- Data augmentation

##  Evaluation Metrics
- Accuracy
- Confusion Matrix
- ROC Curve & AUC

##  Results
Model performance is compared across accuracy, generalization ability, and computational efficiency.

##  Future Extensions
- Real-time gesture recognition using webcam
- Model deployment and optimization
