# Skin-Lesion-Binary-Classification-Using-Deep-Learning-Models
This work aims to employ the concepts of deep learning in order to classify skin lesions as either benign or malignant. It tackles problems like class imbalance and dataset variability using enhanced networks and optimization strategies.
## Project Overview
This project explores the use of deep learning models to classify skin lesions as benign or malignant. By leveraging advanced architectures such as InceptionV3, ResNet50, DenseNet121, and EfficientNetB0, it addresses challenges like dataset imbalance and improves the accuracy of early skin cancer detection.

## Key Features
- **Data Source:** ISIC Archive (International Skin Imaging Collaboration).
- **Models Used:** AlexNet, InceptionV3, ResNet50, DenseNet121, EfficientNetB0.
- **Techniques:** 
  - Focal loss and class-weighted loss for handling class imbalance.
  - Transfer learning and fine-tuning for limited datasets.
  - Ensemble models to boost performance.
- **Evaluation Metrics:** Accuracy, Precision, Recall, and F1 Score.

## Dataset
- Training Set: 7,848 images (balanced between benign and malignant).
- Validation Set: 1,962 images (balanced).
- Test Set: 600 images (from ISIC 2017 dataset).
- Preprocessing: Images resized to 224x224 pixels with normalization and augmentation.

## Results
- Ensemble Model achieved the highest accuracy of **92%**.
- Individual model performance:
  - **InceptionV3:** 89%
  - **ResNet50:** 86%
  - **DenseNet121:** 88%
  - **EfficientNetB0:** 90%
- Challenges: Dataset diversity and computational demands of ensemble models.

## Repository Contents
- **src/**: Python scripts for training and evaluating individual and ensemble models.
- **data/**: Instructions to download and prepare the ISIC dataset.
- **results/**: Plots and metrics showcasing model performance.
- **reports/**: Detailed dissertation and presentation files.

## Requirements
- Python 3.x
- TensorFlow, Keras, NumPy, Pandas, Matplotlib, scikit-learn
