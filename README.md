# Glaucoma Detection Using CNNs

This project implements a deep learning approach for detecting Glaucoma using Convolutional Neural Networks (CNNs). Glaucoma is a chronic eye disease that can lead to vision loss if not diagnosed early. The project uses image processing techniques to analyze retinal images and classify them as either glaucomatous or non-glaucomatous.

## Objective
The main objective of this project is to develop a reliable, automated system for detecting Glaucoma using CNNs, reducing the need for manual screening and improving early diagnosis rates.

## Dataset
The dataset used in this project consists of retinal images that are preprocessed and divided into training, validation, and test sets. The dataset includes:
- **Glaucomatous images** (positive cases)
- **Non-glaucomatous images** (negative cases)

## Approach
### Preprocessing
- Image resizing to fit the input size of the CNN.
- Normalization of pixel values for efficient training.
- Augmentation techniques such as flipping and rotation to enhance the training dataset.

### Model Architecture
A Convolutional Neural Network (CNN) model is used for image classification. The model includes the following key layers:
1. **Convolutional Layers**: For feature extraction using different filters.
2. **Pooling Layers**: To reduce the spatial dimensions of the feature maps.
3. **Dense Layers**: For classification after flattening the extracted features.
4. **Activation Functions**: `ReLU` for non-linearity and `Softmax` for multi-class classification.

The architecture is designed to handle the complexity of retinal images and effectively distinguish between glaucomatous and non-glaucomatous eyes.

### Training and Evaluation
- The model is trained using a categorical cross-entropy loss function with `Adam` optimizer.
- Training accuracy and validation accuracy are monitored to prevent overfitting.
- Evaluation metrics such as accuracy, precision, recall, and F1-score are used to assess the performance of the model.

## How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/Nvm-seff/Glaucoma-Detection-Using-CNNs.git

Results
The model achieves promising results with high accuracy in detecting Glaucoma in retinal images. The final model can be further optimized and deployed for practical use in medical imaging systems.

[Check out the code and detailed implementation here](https://github.com/Nvm-seff/Glaucoma-Detection-Using-CNNs/blob/main/DIP_Project.ipynb)
